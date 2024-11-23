# git-git-it


# Git Quick Reference Guide

## Essential Commands

### Setup & Changes
```bash
git clone <repository-url>        # Clone a repository
git status                        # Check status of working directory
git add .                         # Stage all changes
git commit -m "message"           # Commit staged changes
```

### Branches
```bash
git branch                        # List branches
git checkout -b <branch-name>     # Create and switch to new branch
git checkout <branch-name>        # Switch to branch
```

### Syncing
```bash
git pull origin main              # Get latest main branch
git push origin <branch-name>     # Push your changes to remote
```

## GitHub Workflow

1. Update your main branch:
```bash
git checkout main
git pull
```

2. Create branch:
```bash
git checkout -b your-branch-name
```

3. After making AI-assisted changes:
```bash
git status
git add .
git commit -m "update description"
git push origin your-branch-name
```

4. Create Pull Request:
   - Go to GitHub repository
   - Click "New Pull Request"
   - Select your feature branch
   - Add description of changes
   - Request review

5. After approval, merge through GitHub interface

## Tips
- Always pull main before creating new branches
- Keep commits focused and well-described
- Review AI-generated changes before committing
