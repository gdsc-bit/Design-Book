# Design-Book
##  About Design-Book

The one place where people can look into about the amazing world of Designs and contribute to the learning resources and also the projects that you have build using various design techniques.
  
## How to Contribute?

- Take a look at the existing Issues or create a new Issue.
- [Fork the Repo](https://github.com/gdsc-bit/Design-Book/fork), create a branch for any issue that you are working on and commit your work.
- Create a **[Pull Request]**, which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes that are included in your commits.

## How to make a Pull Request?

**1.** Start by making a fork the [**Design-Book**](https://github.com/gdsc-bit/Design-Book.git) repository. 

**2.** Clone your new fork of the repository:

**3.** Navigate to the new project directory:

```bash
cd Design-Book
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/gdsc-bit/Design-Book.git
```

**5.** Create a new branch:

```bash
git checkout -b YourBranchName
```

**6.** Sync your fork or local repository with the origin repository:

- In your forked repository click on "Fetch upstream"
- Click "Fetch and merge".

### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.

**8.** Stage your changes and commit:

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file

⚠️ **Make sure** not to run the commands ```git add .``` or ```git add *```. Instead, stage your changes for each file/folder

```bash
git add file/folder
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution! 🙌🏼
