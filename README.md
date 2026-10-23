# AutoScholar

A multi-agent research assistant built with Python OOP, ML and RAG.
Enter a research topic and AutoScholar finds papers, reads them, groups them
by theme, and writes a short literature review where every claim is checked
against the real paper text.

## Team

| Person | Role | GitHub |
|---|---|---|
| Mansha (Person 1) | Core architecture, Orchestrator, team lead | @Mansha777 |
| Person 2 | Search, Reader, sources, PDF parsing, vector store | @username |
| Person 3 | Analyst ML module, embeddings, clustering, experiments | @username |
| Person 4 | Critic, Writer, Streamlit dashboard, report and demo | @username |

## Setup

```bash
git clone https://github.com/Mansha777/AutoScholar-.git
cd AutoScholar-
python -m venv venv
venv\Scripts\activate          # Windows
# source venv/bin/activate     # Mac/Linux
pip install -r requirements.txt
```

## Project structure

```
autoscholar/
  agents/    sources/    llms/    analysis/
  core/      models/     ui/      tests/
main.py
```

## Team rules

1. **Never push directly to `main`.** Always use a branch and a pull request.
2. Branch names: `feature/<person>-<thing>`, for example `feature/p2-arxiv-source`.
3. Pull the latest `main` before you start working each day.
4. Do not change base classes or anything in `models/` without telling the group first.
5. Keep commits small, with clear messages.
6. Never commit API keys or `.env` files.

## Status

- [ ] Level 1: search, RAG, summary with citations, Critic
- [ ] Level 2: token tracker, caching, clustering, dashboard
- [ ] Experiments, UML diagram, report
