OctoFit Tracker — project skeleton

This folder holds the OctoFit Tracker application skeleton. It follows the expected structure used by the project instructions.

Structure

octofit-tracker/
- backend/
  - requirements.txt  # Python requirements for the backend
  - (venv is created by the developer when needed)
- frontend/

Quick setup (developer machine)

1) Create a Python virtual environment for the backend (do not change directories in automated scripts; point to path when needed):

```bash
python3 -m venv /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/venv
source /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/venv/bin/activate
pip install -r /workspaces/skills-build-applications-w-copilot-agent-mode/octofit-tracker/backend/requirements.txt
```

Notes
- Forwarded ports used by this project: 8000 (public), 3000 (public), 27017 (private).
- Use Django ORM for DB interactions; follow project-specific instructions in `.github/instructions/`.

This README is minimal — it only documents the skeleton and how to install Python requirements. Further scaffolding (Django project, React app) can be added on this branch.
