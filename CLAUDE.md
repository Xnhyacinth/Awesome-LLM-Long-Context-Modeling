# CLAUDE.md

This file provides guidance to Claude Code when maintaining this repository.

## Commands

- Install linters once:
  - `npm install -g markdownlint-cli`
  - `npm install -g markdownlint-cli2`
- Lint `README.md` only:
  - `markdownlint README.md`
- Lint all Markdown files:
  - `markdownlint-cli2 "**/*.md"`
  - or `markdownlint README.md papers/*.md`

The CI workflow `.github/workflows/pr-check.yml` runs Markdown lint and README size checks on pull requests.

## Repository Structure

- This is an Awesome-style curated list.
- `README.md` is the hub: intro, News, and a chapter index. Keep it well under GitHub's **500 KiB** homepage README render limit.
- Full paper entries live in `papers/*.md` (one file per top-level chapter).
- There is no build system or test suite; most work is Markdown editing.
- Add new papers surgically. Do not rewrite nearby content unless required to fix numbering or date grouping.

## Paper Update Workflow

When adding a new paper:

1. Read the arXiv abstract page first to get:
   - exact title
   - full author list
   - arXiv `v1` submission date
   - conference status if explicitly stated
2. Search for:
   - official GitHub repository
   - official project homepage
3. Update in these places:
   - `README.md` → `## 📢 News` (by arXiv v1 date)
   - the best-matching chapter file under `papers/` (append at end of the target subsection)
   - if you add a new subsection heading (`####` / `#####`), also update the `<!-- chapter-toc -->` block at the top of that chapter file
   - if you add a new top-level chapter (rare), also update Contents and the Papers chapter groups in `README.md`
4. Keep numbering continuous inside the target subsection.
5. Do not change existing items except for necessary numbering, date-group cleanup, or obvious formatting fixes.

## News Rules

- Always group papers in `News` by the real arXiv `v1` submission date, not by the day you update the repo.
- Keep date groups in strict reverse chronological order.
- Never create duplicate date blocks; merge papers into the existing date block if the date already exists.
- Use the format:
  - `- **[YYYY.MM.DD]**`
  - `- Paper: [Title](arXiv URL) ...`

## Section Classification

- Classify by paper content, not only by the user's requested section if the content clearly belongs elsewhere.
- Map to `papers/` files by chapter number, for example:
  - prompt/context compression -> `papers/11-context-compression.md`
  - model compression / pruning / quantization -> `papers/12-model-compression.md`
  - long chain-of-thought compression or adaptive thinking -> `papers/13-long-reasoning.md`
  - KV cache compression / eviction / serving / budgeting -> `papers/03-kv-cache.md` (or sparse/IO-aware attention in `papers/02-efficient-attention.md`)
  - long video or image token reduction -> `papers/14-long-video-image.md`
  - surveys only -> `papers/01-survey.md`
- If a paper is not actually a survey, do not put it in Survey Papers even if the user casually says "add to survey".

## Entry Formatting

- Append new papers at the end of the target subsection in the chapter file.
- Preserve the existing Markdown style.
- Include full author names in section entries.
- If conference acceptance is explicit, use it; otherwise use `Arxiv YEAR`.
- Add badges only for credible official links:
  - GitHub repo -> stars badge
  - project page -> static homepage badge
- If no reliable repo or homepage is found, do not invent one and do not add a badge.

## Git Workflow

- `CLAUDE.md` is intended to be tracked by git so other contributors can reuse the guidance.
- Personal local-only Claude settings should go under `.claude/`, not `CLAUDE.md`.
- When pushing updates for this repo:
  - `git add .`
  - `git commit -s -m "$CURRENT_DATE"`
  - `git push origin main`
- Do not add extra co-author lines unless explicitly requested.
- Do not commit `.DS_Store` or backup files.
