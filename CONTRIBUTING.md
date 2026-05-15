# Contributing

Thanks for helping improve this long-context modeling paper list.

## Adding A Paper

Please include:

- Paper title with an arXiv, OpenReview, ACL Anthology, ACM, or project page link.
- Author list, venue, and year.
- GitHub badge when code is available.
- Homepage badge when a project page, demo, or model page is available.
- The most specific section or subsection in `README.md`.

Recommended entry format:

```markdown
1. [**Paper Title.**](https://arxiv.org/abs/xxxx.xxxxx) _Author A, Author B._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/owner/repo)](https://github.com/owner/repo)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://project-homepage.example/)
```

## Classification Guidelines

- Prefer the most method-specific subsection over broad topical placement.
- Put training-time long-context extension in `7. Long-Context Training`, not in architecture sections.
- Put KV-cache eviction, selection, quantization, and offloading in `3. KV-Cache Optimization`.
- Put prompt, context, visual-token, and RAG-aware context compression in `11. Context Compression`.
- Put model weight quantization, distillation, and pruning in `12. Model Compression for Long Context`.
- Avoid duplicate entries across sections; if a paper spans multiple areas, choose its primary contribution.

## Checklist

- Keep the table of contents and body headings synchronized.
- Preserve the 20-chapter top-level taxonomy.
- Use GitHub and homepage badges when available.
- Run the repository checks before submitting a pull request.
