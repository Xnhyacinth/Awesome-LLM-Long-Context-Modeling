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

The CI workflow `.github/workflows/readme-check.yml` runs Markdown lint checks on pull requests.

## Repository Structure

- This is an Awesome-style curated list.
- The primary artifact is `README.md`.
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
3. Update `README.md` in two places:
   - `## 📢 News`
   - the best-matching main section
4. Keep numbering continuous inside the target section.
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
- Use these common routing rules:
  - prompt/context compression -> `9.1 Context`
  - model compression / pruning / quantization -> `9.2 Model`
  - long chain-of-thought compression or memory for reasoning -> `9.3 Long CoT` or `13.*` depending on focus
  - KV cache compression / eviction / serving / budgeting -> `2.4 IO-Aware Attention`
  - long video or image token reduction -> `10.*`
  - surveys only -> `1. Survey Papers`
- If a paper is not actually a survey, do not put it in `Survey Papers` even if the user casually says "add to survey".

## Entry Formatting

- Append new papers at the end of the target section.
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
