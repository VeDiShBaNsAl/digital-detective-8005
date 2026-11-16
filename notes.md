
## Task 6.2 — Create and use a branch
* **Branch created:** `update-about` (`git checkout -b update-about`)
* **File modified:** Root `README.md` (Added "My Learning" section detailing OS, Python, and Git milestones).
* **Commands used:** `git status`, `git add README.md`, `git commit -m "..."`, `git push -u origin update-about`
* **Verification:** Successfully pushed the new branch to GitHub and verified branch tracking.

## Task 6.3 — Create a Pull Request

### GitHub Actions Performed:
* Opened a Pull Request from `update-about` into `main` on GitHub.
* Added a descriptive title and summary of changes.
* Reviewed and merged the PR into `main`, then synchronized local changes using `git checkout main` and `git pull`.

### Conceptual Explanations:
* **What is a branch?**
  A branch is an independent, isolated line of development separate from the main codebase (`main`). It allows developers to implement new features, fix bugs, or test changes without altering or breaking the stable production code.
* **What is a Pull Request (PR)?**
  A Pull Request is a collaborative feature on platforms like GitHub where developers propose changes made in a branch to be merged into another branch (such as `main`). It serves as a workspace for code review, discussion, automated testing, and feedback before integration.
* **Why are they useful when people work on the same project?**
  Branches and Pull Requests prevent team members from stepping on each other's toes by keeping individual work isolated. PRs facilitate peer code review, catch bugs early through automated checks, ensure code quality standards, and maintain an organized history of decisions and changes made across the project.
