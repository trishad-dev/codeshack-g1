
# Git Basics for Beginners

This guide explains common Git commands used in software development.

## 1. Check Git Version

```bash
git --version
```

Displays the installed Git version.

## 2. Check Repository Status

```bash
git status
```

Shows the current branch and the state of files.

## 3. Create a Branch

```bash
git switch -c feature/my-feature
```

Creates a new branch and switches to it.

## 4. Stage Changes

```bash
git add git-basics.md
```

Stages the file for the next commit.

## 5. Commit Changes

```bash
git commit -m "Add Git basics guide"
```

Records staged changes in the repository history.

## 6. View Commit History

```bash
git log --oneline
```

Displays commits in a compact format.

## 7. View File Differences

```bash
git diff
```

Shows unstaged changes to tracked files.

## 8. Push a Branch

```bash
git push -u origin feature/my-feature
```

Uploads the branch to GitHub and configures upstream tracking.

## 9. Fetch Remote Changes

```bash
git fetch origin
```

Downloads remote updates without merging them into the current branch.

## 10. Pull Remote Changes

```bash
git pull
```

Fetches and integrates changes from the configured upstream branch.
