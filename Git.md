# Git Interview Questions

Q. How does Git differ from SVN?

<details><summary>Answer</summary>

# Git

1. Git is a distributed version control system.
2. This means that Git allows multiple developers to work on the same codebase simultaneously.
3. Git also has a more complex branching and merging system.
4. Git also has a more robust history tracking system.
5. Git also has a more robust security model.
6. Git also has a more robust collaboration model.

# SVN

1. SVN is a centralized version control system.
2. This means that SVN requires a single central repository.
3. SVN also has a simpler branching model.
4. SVN also has a simpler history tracking system.
5. SVN also has a simpler security model.
6. SVN also has a simpler collaboration model.

</details>

---

Q. What is the difference between Git and GitHub?

<details><summary>Answer</summary>

| Feature           | Git                                      | GitHub                                                |
| ----------------- | ---------------------------------------- | ----------------------------------------------------- |
| Type              | Version control system                   | Cloud-based Git repository hosting                    |
| Purpose           | Tracks changes and manages code versions | Enables collaboration and hosting of Git repositories |
| Dependancy        | Works without GitHub                     | Depends on Git for version control                    |
| Internet Required | No                                       | Yes                                                   |
| Interface         | Command-line tool                        | Web-based GUI (also CLI and desktop app)              |
| Collaboaration    | Local collaboration possible             | Supports global collaboration                         |
| Features          | Branching, merging, version tracking     | Pull requests, code reviews, issue tracking, wikis    |
| Examples          | Local development workflow               | Open-source projects, team collaboration              |

</details>

---

Q. What is the difference between `git pull` and `git fetch`?

<details><summary>Answer</summary>

`git fetch` is the command that tells your local git repository to retrieve the latest metadata info from a remote repository, but it doesn't integrate any of this new data into your working files. It's more like just checking to see if there are any changes available.
`git pull` on the other hand does that AND brings a copy of those changes from the remote repository and updates your current HEAD branch.

</details>

---

Q. What is the difference between `git status` and `git diff`?

<details><summary>Answer</summary>

| Feature               | Git Status                            | Git Diff                              |
| --------------------- | ------------------------------------- | ------------------------------------- |
| Purpose               | Shows an overview of the repo's state | Shows specific line-by-line changes   |
| Focus                 | General summary of changes            | Detailed differences in file contents |
| Shows Staging Area    | Yes (lists files staged for commit)   | Yes (with --staged option)            |
| Shows Untracked Files | Yes                                   | No                                    |
| Shows Line Changes    | No                                    | Yes                                   |
| Use Case              | Understand the overall status         | Inspect detailed changes in files     |

</details>

---

Q. What is the difference between `git commit -m` and `git commit`?

<details><summary>Answer</summary>

`git commit -m "Your commit message"`:

- -m`is a shorthand for`--message` and is used to specify the commit message directly on the command line.
- You provide the message in double quotes (`"`) to enclose the message.
- Example: `git commit -m "Add new feature"`

`git commit`:

- When you run git commit without the -m option, Git will open the default text editor (as configured in your Git settings) for you to write your commit message.
- This allows you to write a more detailed and descriptive commit message.
- After you finish writing the message, you save and close the editor to commit the changes.
- Example: `git commit`

</details>

---
