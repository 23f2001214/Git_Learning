# GitHub Notes

## What is GitHub?

GitHub is a cloud-based platform that helps developers:

- Store code online
- Collaborate with others
- Track project changes
- Manage software projects
- Contribute to open-source projects

GitHub uses **Git** for version control.

---

#  Git vs GitHub

| Git | GitHub |
|------|---------|
| Version Control System | Cloud Hosting Platform |
| Works locally | Works online |
| Tracks changes | Stores repositories |
| Command-line tool | Web-based platform |
| Created by Linus Torvalds | Owned by Microsoft |

---

# Repository (Repo)

A repository is a project folder stored on GitHub.

It contains:
- Source code
- README files
- Images
- Documentation
- Commit history

Example Repository URL:

```bash
https://github.com/username/repository-name
```

---

# README.md

`README.md` is the main documentation file of a project.

It usually contains:
- Project name
- Description
- Installation steps
- Features
- Usage instructions
- Screenshots

Markdown extension:

```text
.md
```

---

# Clone Repository

Clone means copying a GitHub repository to your local computer.

## Command

```bash
git clone <repository-url>
```

## Example

```bash
git clone https://github.com/user/project.git
```

---

# GitHub Workflow

```text
Create Repository
       ↓
Clone Repository
       ↓
Create Branch
       ↓
Make Changes
       ↓
Commit Changes
       ↓
Push Changes
       ↓
Create Pull Request
       ↓
Merge Changes
```

---

# Branch

A branch allows developers to work independently without affecting the main project.

## Create Branch

```bash
git branch feature-login
```

## Switch Branch

```bash
git checkout feature-login
```

## Create + Switch

```bash
git checkout -b feature-login
```

---

# Commit

A commit saves project changes in Git.

## Command

```bash
git commit -m "Added login feature"
```

### Good Commit Message Examples

```bash
git commit -m "Fixed navbar bug"
git commit -m "Updated README"
git commit -m "Added authentication system"
```

---

# Push

Push uploads local changes to GitHub.

## Command

```bash
git push origin main
```

---

# Pull

Pull downloads latest changes from GitHub.

## Command

```bash
git pull origin main
```

---

# Merge

Merge combines branches together.

## Command

```bash
git merge feature-login
```

---

#  Fork

A fork is your own copy of another person's repository.

Forking is mainly used in:
- Open-source contributions
- Experimenting safely

---

#  Pull Request (PR)

A Pull Request is a request to merge your code changes into another branch.

## PR Workflow

1. Fork Repository
2. Clone Repository
3. Create Branch
4. Make Changes
5. Commit Changes
6. Push Changes
7. Open Pull Request

---

# Issues

Issues are used to:
- Report bugs
- Request features
- Discuss improvements

Example:
- "Navbar not responsive"
- "Add dark mode feature"

---

#  Star

You can star repositories to:
- Save useful projects
- Support developers
- Bookmark repositories

---

#  Watch

Watch allows you to receive notifications about repository activity.

---

#  Releases

Releases are versions of a project shared publicly.

Example:
- v1.0.0
- v2.0.1

---

#  .gitignore

`.gitignore` prevents files from being uploaded to GitHub.

Example:

```gitignore
node_modules/
.env
dist/
```

---

#  Remote Repository

Connect local project to GitHub repository.

## Add Remote

```bash
git remote add origin <repository-url>
```

## Check Remote

```bash
git remote -v
```

---

#  Common Git Commands

## Initialize Git

```bash
git init
```

## Check Status

```bash
git status
```

## Add All Files

```bash
git add .
```

## Add Specific File

```bash
git add file.txt
```

## Commit Changes

```bash
git commit -m "message"
```

## Push Changes

```bash
git push
```

## Pull Changes

```bash
git pull
```

## View Branches

```bash
git branch
```

## Delete Branch

```bash
git branch -d branch-name
```

---

#  Open Source

Open-source means source code is publicly available for anyone to:
- View
- Modify
- Improve
- Share

Popular open-source projects:
- Linux
- React
- VS Code

---

#  Collaboration on GitHub

GitHub allows teams to:
- Work together
- Review code
- Discuss changes
- Track progress

---

#  GitHub Authentication

GitHub supports:
- Username & Password
- Personal Access Token (PAT)
- SSH Keys

---

#  SSH Key Setup

Generate SSH Key:

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

Add SSH Key to GitHub for secure authentication.

---

#  GitHub Pages

GitHub Pages allows hosting static websites directly from a repository.

Supports:
- HTML
- CSS
- JavaScript

Example uses:
- Portfolio websites
- Documentation
- Blogs

---

#  GitHub Actions

GitHub Actions is used for automation.

Examples:
- Run tests automatically
- Deploy applications
- Build projects

Workflow location:

```text
.github/workflows/
```

---
























