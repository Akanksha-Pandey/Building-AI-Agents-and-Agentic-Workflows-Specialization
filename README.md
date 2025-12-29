# Building AI Agents and Agentic Workflows — Specialization Notes

This repository is my workspace for the Coursera specialization "Building AI Agents and Agentic Workflows".

Course link: https://www.coursera.org/specializations/building-ai-agents-and-agentic-workflows

Purpose
- Keep exercises, notes, example code, and small projects while working through the specialization.
- Provide a reproducible place to store notebooks, scripts, and configuration used to follow along with the course.

What you'll find (or should add)
- `README.md` — this file (overview and usage).
- `notebooks/` — Jupyter notebooks for assignments, labs, and experiments (create as you go).
- `examples/` — small runnable scripts or demos extracted from notebooks.
- `data/` — small datasets or links to datasets used in exercises (do not store large files here).
- `requirements.txt` or `environment.yml` — Python dependencies (add if you create reproducible envs).
- `keys.json` — local keys/config (already present). Do NOT commit secrets to a public repo.

How I plan to organize work
- One notebook per course module or assignment, named with a prefix `courseX_moduleY_...`.
- Short runnable examples in `examples/` for tasks I want to preserve as scripts.
- Use `data/README.md` to document dataset sources and download instructions.

Quick start
1. Clone the repo:

```bash
git clone https://github.com/Akanksha-Pandey/Building-AI-Agents-and-Agentic-Workflows-Specialization.git
cd Building-AI-Agents-and-Agentic-Workflows-Specialization
```

2. (Optional) Create a Python virtual environment and install dependencies if you add `requirements.txt`:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

3. Run notebooks (if you add them):

```bash
jupyter lab
# or
jupyter notebook
```

Notes & best practices
- Never commit API keys, passwords, or other secrets. Keep them in `keys.json` locally and add `keys.json` to `.gitignore` if this repo will be public.
- Prefer small sample data in `data/` and provide scripts to download larger datasets.
- Add a `requirements.txt` when dependencies stabilize so environments are reproducible.

License & credits
- This repo is my personal workspace for the Coursera specialization. Course content and materials are owned by the course providers (Coursera / instructors). Use this repo only for personal learning and do not redistribute course assets that are restricted by course terms.

Next steps I can help with
- Create the suggested folder structure and a template `requirements.txt`.
- Add a starter `.gitignore` that excludes `__pycache__/`, `.venv/`, and `keys.json`.
- Commit the README changes and create an initial commit message.

If you'd like, I can apply any of those next steps now — tell me which one to do.
