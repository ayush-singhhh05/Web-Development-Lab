# P03: Feature-Branch Git Workflow

**Student:** Ayush Kumar  
**Subject:** Programming for Web Development - I Laboratory

## Aim
To practice Git feature branches and learn how to merge changes into the main branch using a pull request.

## What I Did
For this practical, I created the branch `feature/p03-git-workflow`, added this README on that branch, and opened a pull request to merge the documentation into `main`.

## Commands to Understand
```bash
git switch main
git pull origin main
git switch -c feature/p03-git-workflow
git add P03/README.md
git commit -m "Document P03 feature-branch workflow"
git push -u origin feature/p03-git-workflow
```

These commands show the *equivalent local Git workflow*. In this repository, the branch and README were created using the GitHub integration instead of the local terminal.

## Important Git Terms
- **main**: The primary branch of the project.
- **feature branch**: A separate branch for working on a change.
- **commit**: A saved checkpoint in Git history.
- **pull request**: A request to review and merge a branch into another branch.
- **merge**: Combining the changes from a feature branch into `main`.

## Result
A feature branch and pull request were used to add the P03 practical documentation without changing the existing `index.html` bio page.
