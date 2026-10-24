# Geek Room AI-ML Department (2026-27)

Repository for the **AI-ML Department of Geek Room** for the 2026-27 session. Members submit their weekly tasks, notebooks, and presentations here so everything is tracked in one place.

## Repository Structure

```
members/
└── <Your Name>/
    ├── task-1/
    │   ├── solution.ipynb      # code / notebook
    │   ├── presentation.pdf    # slides
    │   └── README.md           # short explanation of your approach
    └── task-2/
        └── ...
```

- Use your **full name** as the folder name (same as the example `members/Aryan Das/`).
- One folder per task: `task-1`, `task-2`, and so on.
- Each task folder should contain your **code**, your **presentation**, and a short **README** describing what you did.

## How to Submit

1. **Fork** this repository.
2. Add your work under `members/<Your Name>/task-N/`.
3. **Open a Pull Request** against `main` titled `<Your Name> - Task N`.
4. Wait for a maintainer to review and merge.

```bash
git clone https://github.com/<your-username>/<repo>.git
cd <repo>
git checkout -b task1-yourname
# add your files
git add "members/<Your Name>/task-1"
git commit -m "Add Task 1 - <Your Name>"
git push origin task1-yourname
```

## Rules

- Do **not** edit other members' folders.
- Keep large datasets out of the repo — link to them instead, or add them to `.gitignore`.
- No secrets, API keys, or credentials in your code.
- Name files clearly (`solution.ipynb`, `presentation.pdf`); avoid `final_final_v2.ipynb`.
- One PR per task, and keep your PR focused on that task only.
- Commit messages should be short and descriptive.
