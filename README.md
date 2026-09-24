
# Git Commands

| # | Command | Explanation |
|---|---|---|
| 1 | `mkdir git-workshop` | Creates a new directory called `git-workshop`. |
| 2 | `cd git-workshop` | Moves into the `git-workshop` directory. |
| 3 | `git init` | Initializes a new Git repository in the directory. |
| 4 | `echo gitCommands.txt > .gitignore` | Creates `.gitignore` and adds `gitCommands.txt` to it. |
| 5 | `echo .env >> .gitignore` | Adds `.env` to the existing `.gitignore` file. |
| 6 | `git add .gitignore` | Stages the `.gitignore` file for committing. |
| 7 | `git commit -m "Initial commit; with gitignore"` | Creates the initial commit containing `.gitignore`. |
| 8 | `git status` | Shows the current state of the Git repository. |
| 9 | `git remote add origin https://github.com/rep/git-workshop.git` | Adds the GitHub repository as the remote named `origin`. |
| 10 | `git remote -v` | Displays the configured remote repository URLs. |
| 11 | `git branch -M main` | Renames the current branch to `main`. |
| 12 | `git push -u origin main` | Pushes the `main` branch to GitHub and sets the upstream branch. |
| 13 | `git add README.md` | Stages `README.md` for the next commit. |
| 14 | `git commit -m "Added README.md file"` | Creates a commit containing the staged `README.md`. |
