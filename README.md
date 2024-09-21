
#### Using Git in VS Code Command Line. Git tutorial.

Follow these steps to use Git in the VS Code integrated terminal (CMD):

## 1. Install Git
- If you haven’t already, download and install Git from [Git's official website](https://git-scm.com/).

## 2. Check Git Installation
- Open the **integrated terminal** in VS Code:
  - Press `Ctrl + ` (backtick) to open the terminal.
- Check if Git is installed by typing:

  ```bash
  git --version
  ```

- If Git is installed correctly, you will see a version number.

## 3. Initialize a Git Repository
- Navigate to your project folder in the terminal:

  ```bash
  cd path/to/your/project
  ```

- Initialize a Git repository:

  ```bash
  git init
  ```

## 4. Check Git Status
To see the current status of your repository (e.g., untracked files, modifications):

```bash
git status
```

## 5. Stage Files for Commit
- To add all files to the staging area:

  ```bash
  git add .
  ```

- To add a specific file:

  ```bash
  git add filename.extension
  ```

## 6. Commit Changes
After staging, commit the changes with a message:

```bash
git commit -m "Your first commit message"
```

## 7. Set Remote Repository
If you’re using a remote Git service like GitHub, add the remote repository:

```bash
git remote add origin https://github.com/your-username/repo-name.git
```

## 8. Push Changes to Remote
Push your commits to the remote repository:

```bash
git push -u origin master
```

## 9. Pull Changes from Remote
To pull changes from the remote repository:

```bash
git pull origin master
```

## 10. Create and Switch Branches
- To create a new branch:

  ```bash
  git branch new-branch-name
  ```

- To switch to the newly created branch:

  ```bash
  git checkout new-branch-name
  ```

## 11. Merge Branches
To merge another branch into your current branch:

```bash
git merge branch-name
```

## 12. View Commit History
To view the history of commits:

```bash
git log
```

---

**Note**: You can also access most Git functionality through the VS Code **Source Control** tab (on the left sidebar).
```

This is the full guide in **Markdown format** on how to use Git in the VS Code terminal.
Thank You to read.
