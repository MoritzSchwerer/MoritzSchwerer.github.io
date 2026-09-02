# Resume Workflow

This folder contains simple Markdown resume sources. The public site links to the generated PDF in `assets/`.

## Files

- `moritz-schwerer-resume-robot-learning.md`: main one-page resume for robot learning, humanoid RL, sim-to-real, and research engineering roles.
- `moritz-schwerer-resume-rl-research.md`: more research-heavy variant for reinforcement learning / general intelligence labs.
- `application-blueprint.md`: role targeting, keyword checklist, and tailoring notes.

## Build

From the repository root:

```sh
pandoc resume/moritz-schwerer-resume-robot-learning.md \
  -o assets/moritz-schwerer-resume.pdf \
  --pdf-engine=pdflatex \
  -V geometry:'a4paper,margin=0.45in' \
  -V fontsize=9pt \
  -V linestretch=0.94
```

Before sending applications, confirm dates, grades, and any project links that should be role-specific.
