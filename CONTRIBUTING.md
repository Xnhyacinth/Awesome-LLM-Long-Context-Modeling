# Contributing

Thanks for helping improve this long-context modeling paper list.

## Repository Layout

- `README.md` — hub page (intro, News, chapter index). Must stay under **500 KiB** so GitHub can render it on the repository homepage.
- `papers/*.md` — full paper entries, one file per top-level chapter.

## Adding A Paper

Please include:

- Paper title with an arXiv, OpenReview, ACL Anthology, ACM, or project page link.
- Author list, venue, and year.
- GitHub badge when code is available.
- Homepage badge when a project page, demo, or model page is available.
- Place the entry in the most specific subsection of the matching `papers/*.md` chapter.
- Also add a News bullet in `README.md` grouped by the real arXiv `v1` date.

Recommended entry format:

```markdown
1. [**Paper Title.**](https://arxiv.org/abs/xxxx.xxxxx) _Author A, Author B._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/owner/repo)](https://github.com/owner/repo)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://project-homepage.example/)
```

## Classification Guidelines

- Prefer the most method-specific subsection over broad topical placement.
- Put training-time long-context extension in `papers/07-long-context-training.md`, not in architecture chapters.
- Put KV-cache eviction, selection, quantization, and offloading in `papers/03-kv-cache.md`.
- Put prompt, context, visual-token, and RAG-aware context compression in `papers/11-context-compression.md`.
- Put model weight quantization, distillation, and pruning in `papers/12-model-compression.md`.
- Avoid duplicate entries across sections; if a paper spans multiple areas, choose its primary contribution.

## Checklist

- Preserve the 20-chapter top-level taxonomy and Contents links in `README.md`.
- If you add a new `####` / `#####` subsection, update the `<!-- chapter-toc -->` block at the top of that chapter file.
- Use GitHub and homepage badges when available.
- Run repository checks before submitting a pull request:
  - `markdownlint README.md papers/*.md`
  - `test $(wc -c < README.md) -le 512000`
