# Git Workflow Guide

## 1. Check Repository Status
Use `git status` to check the current branch and identify modified, staged, or committed files.

## 2. Create a Feature Branch
Use `git switch -c feature/branch-name` to create and switch to a new feature branch.

## 3. Stage Changes
Use `git add filename` to stage a specific file for the next commit.

## 4. Commit Changes
Use `git commit -m "Descriptive commit message"` to save staged changes in the local repository.

## 5. View Commit History
Use `git log --oneline` to view a concise history of commits.

## 6. Review Changes
Use `git diff` to inspect unstaged changes before staging them.

## 7. Fetch Remote Updates
Use `git fetch origin` to download information about remote changes without integrating them into the current branch.

## 8. Pull Remote Updates
Use `git pull` to fetch and integrate updates from the configured remote branch.

## 9. Push Changes
Use `git push` to upload committed changes to the remote branch.

## 10. Collaboration Best Practices
- Work on a separate feature branch.
- Write clear, meaningful commit messages.
- Review changes before committing.
- Keep documentation organized.
- Avoid committing directly to `main`.
- Coordinate with teammates before integrating changes.