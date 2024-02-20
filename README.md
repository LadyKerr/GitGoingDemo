# GitGoing 🏃🏽‍♀️💨
GitGoing is a beginner-friendly project focused on tracking progress and learning how to use git and GitHub.

## Getting Started 🛠️

You will need to have git installed on your local machine. You can download it [here](https://git-scm.com/downloads).

Once you have git installed, you will need to configure git. You can do this by running the following commands in your terminal.

```bash
git config --global user.name "Your Name"
git config --global user.email "Your Email"
```

Then, start by cloning the repository to your local machine.
    
```bash
    git clone https://github.com/LadyKerr/GitGoing.git
 ```


# Practice the git flow by following the steps below 🚀

### Step 1: Create a new branch and switch to new branch

Create a new branch using the following command:

```bash
git checkout -b <your-new-branch-name>
```

Once you create your new branch, you will be switched to that branch with the following command:

```bash
git switch <your-new-branch-name>
```

### Step 2: Make changes

You can add a new file, edit an existing file, or delete a file.
To keep things simple, let's edit the `index.html` file by changing the name to "GitGoing" on line 10.

### Step 3: Stage your changes

Once you update the name, stage your changes using the following command:

```bash
git add .
```

Or, you can stage the individual file you changed by using the following command:

```bash
git add index.html
```

### Step 4: Commit your changes

Commit your changes using the following command:

```bash
git commit -m "Your commit message"
```

### Step 5: Push your changes

Push your changes to the remote repository using the following command:

```bash
git push origin <your-branch-name>
```

### Step 6: Create a pull request

Create a pull request on GitHub.

### Step 7: Review and merge your pull request

Review and merge your pull request on GitHub.

### Step 8: Delete your branch

Delete your branch using the following command:

```bash
git branch -d <your-branch-name>
```

## Learning Resources:
- [Git Cheatsheet ↗](https://education.github.com/git-cheat-sheet-education.pdf)
- [Introduction to Git and GitHub ↗](https://github.com/skills/introduction-to-github)
- [GitHub Skills Courses ↗](https://skills.github.com/)
- [GitHub Foundations Certificate ↗](https://learn.microsoft.com/en-us/collections/o1njfe825p602p)


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
