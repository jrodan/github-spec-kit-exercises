
# Solution: Lab 1 — Install and Initialize Spec Kit

## Step-by-step Solution

1. **Install Spec Kit CLI**
    - With pipx (recommended):
       ```bash
       pipx install git+https://github.com/github/spec-kit.git
       ```
    - Or with pip:
       ```bash
       pip install --user git+https://github.com/github/spec-kit.git
       ```
2. **Verify installation**
    - Run:
       ```bash
       spec-kit --help
       ```
    - If not found, try:
       ```bash
       ~/.local/pipx/venvs/specify-cli/bin/specify --help
       ```
3. **Initialize a new project**
    - Run:
       ```bash
       ~/.local/pipx/venvs/specify-cli/bin/specify init my-spec-kit-demo
       ```
    - This creates a `.specify/` folder and starter files.
4. **Check and update the Constitution**
    - Open `.specify/memory/constitution.md` and review the rules for your scenario (e.g., Orders API for an online shop):
       - Who owns the spec?
       - Who reviews and approves changes?
       - What is the process for proposing and accepting changes?
       - What is the code of conduct for contributors?
    - Update the file to reflect your team/project's actual governance.

## Expected Outcome
- `.specify/` folder and initial files exist.
- Constitution is tailored to your project/team.
