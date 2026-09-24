
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
| 15 | `echo Hello World > index.html` | Creates `index.html` containing `Hello World`. |
| 16 | `git commit -m "Added index.html, modified README.md to add line 4 to 14"` | Creates a commit with the staged changes. |
| 17 | `type nul > style.css` | Creates an empty `style.css` file on Windows. |
| 18 | `git add styles.css` | Stages `styles.css` for the next commit. |
| 19 | `echo body { > styles.css` | Adds the opening of the CSS `body` rule to `styles.css`. |
| 20 | `echo     margin: 0; >> styles.css` | Adds `margin: 0` to the CSS rule. |
| 21 | `echo     padding: 0; >> styles.css` | Adds `padding: 0` to the CSS rule. |
| 22 | `echo } >> styles.css` | Adds the closing brace to the CSS rule. |
| 23 | `git commit -m "Added margin: 0; padding: 0; to styles.css"` | Creates a commit with the staged CSS changes. |
| 24 | `git push -u origin main` | Pushes the `main` branch and its commits to GitHub. |
