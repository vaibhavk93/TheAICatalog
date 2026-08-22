# The AI Catalog

An interactive, single-page guide to building and understanding chatbots and AI agents —
one story, ten words, six questions, five traps, and 37 drawers covering RAG, agents,
context engineering, evaluation, safety, the frontend, infra/deployment, running one in
production, and the full AI Product Manager / AI Consultant track (strategy, platform
decisions, pricing, governance, and advising from outside a company).

**Live:** https://vaibhavk93.github.io/TheAICatalog/

Want the narrower, chatbot-building-only version instead (no AI-leadership, generative-
media, or document-AI drawers)? That's
[vaibhavk93/learnChatBot](https://github.com/vaibhavk93/learnChatBot) — same source, same
build, a 31-drawer subset.

## Files

| File | What it is |
|---|---|
| [site/catalog.html](site/catalog.html) | Source. Edit this. |
| [index.html](index.html) | Built output, served by GitHub Pages from the repo root. |
| [build_docs.py](build_docs.py) | Rebuilds `index.html` from `site/catalog.html`. Run it after every edit to the source. |

**⚠ Pages must be set to deploy from `main` / `/(root)`, not `/docs`** — there's no
`docs/` folder here. If Pages is pointed at `/docs`, the live site 404s.

```bash
python3 build_docs.py
```
