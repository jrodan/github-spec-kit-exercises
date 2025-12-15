
# Context
**Spec Kit Phase:** Constitution (`/speckit.constitution`)
**Learning Goal:** Establish project governing principles and development guidelines before specifying or building the API.

# Lab 1 — Install and Initialize Spec Kit

**Estimated time:** 5–8 minutes

## Goal
Install the Spec Kit CLI and initialize a new Spec Kit project.

## Steps
1. **Install Spec Kit CLI** (choose one):
   - With pipx (recommended):
     ```bash
     pipx install git+https://github.com/github/spec-kit.git
     ```
   - Or with pip:
     ```bash
     pip install --user git+https://github.com/github/spec-kit.git
     ```
2. **Verify installation:**
   ```bash
   spec-kit --help
   ```
3. **Initialize a new Spec Kit project:**
   ```bash
   specify init my-spec-kit-demo
   ```
   - This creates a `.specify/` folder and starter files.
4. **Check and update the Constitution file:**
   - Open `.specify/memory/constitution.md` (created by `specify init`).
   - Review the rules for your scenario (e.g., Orders API for an online shop):
     - Who owns the spec?
     - Who reviews and approves changes?
     - What is the process for proposing and accepting changes?
     - What is the code of conduct for contributors?
   - Update the file to reflect your team/project's actual governance.

**Checklist/Clarification:**
- Discuss the above questions with your team or stakeholders.
- Document the agreed rules in `.specify/memory/constitution.md`.
- Revisit and update the file as the project evolves.

**Sample prompt for the team/AI:**
> "Draft a Constitution for our Orders API project. The API Team owns the spec, changes require review from both API and Consumer teams, and all contributors must document changes and follow our code of conduct."

## Expected outcome
- `.specify/` folder and initial Spec Kit files exist in your directory.

## Troubleshooting
- If you get a command not found error, check your PATH or try restarting your terminal.
