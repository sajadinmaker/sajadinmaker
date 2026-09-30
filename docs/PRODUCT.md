# Profile (`sajadinmaker`) — Product Documentation

> Personal-brand landing repo. Single-file product: `README.md` renders as the GitHub profile.

## 1. What this product is

Elevator pitch — “Backend systems first, then AI + usable interface” — with Core (Python/FastAPI/Postgres/Redis/Celery), AI (RAG/FAISS/OpenAI), Product (TS/Next.js), Practice (pytest/Actions/JWT/Prometheus), Selected-work table (HookFlow, Lexora, neuDB+PyPI, EsenceLab), Currently-building, and Links (Portfolio, LinkedIn, Email).

**Users:** profile visitors → portfolio / project repos / contact.

## 2. How to serve users

- No build/run. Edit `README.md` only; GitHub renders automatically.
- Keep in sync with `../site/index.html`: project list, blurbs, links, “currently building”.
- Link hygiene: Portfolio (`https://sajadinmaker.github.io/`), project repos, PyPI `neudb`, LinkedIn, `mailto:abdullasajad01@gmail.com`. Check quarterly (no CI link-check yet).
- Verify: `npx markdownlint README.md` or VS Code preview; confirm table + links render on github.com/sajadinmaker.

## 3. Roadmap

Add link-check CI, pin “currently building” to HookFlow dashboard milestone, mirror site resume PDF version.
