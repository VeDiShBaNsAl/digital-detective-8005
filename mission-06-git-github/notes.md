# Mission 6 - Version Control with Git Notes

## Task 6.1 — Understand the basic Git workflow

### Git Operations Table:
| Git operation | What it does in your own words |
| :--- | :--- |
| **Check repository status** | Inspects the working directory and staging area to show which files are modified, untracked, or staged and ready for commit. |
| **Stage selected changes** | Adds specific modified or new files to the staging area (`git add`), preparing them to be included in the next snapshot. |
| **Create a commit** | Permanently records the staged snapshot into the repository history (`git commit`) with a unique ID and descriptive message. |
| **View commit history** | Displays the chronological timeline of previous commits (`git log`), showing commit hashes, author details, timestamps, and messages. |

### Difference Between Staging and Committing:
* **Staging (`git add`):** Acts as a staging dock or workspace preparation step. It groups specific changes you want to include in your next save without permanently locking them into the project history yet.
* **Committing (`git commit`):** Takes everything currently in the staging area and permanently saves it as an official, version-controlled checkpoint in your repository's history graph.
