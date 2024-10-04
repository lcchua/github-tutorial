# Repo name:  github-tutorial
_This repo is for the CE7 Module 3.2 assignment._

![image](https://github.com/user-attachments/assets/151153c6-8990-4703-97da-7878bc8dc9e0)

## What is GitHub Authentication and how what methods available to be implemented?

> [GitHub authentication] is a security mechanism that verifies user identities before granting
> access to accounts and resources on the platform. This process is essential for protecting
> sensitive data and ensuring that only authorized users can perform operations on repositories.
> GitHub supports various methods of authentication, allowing users to choose the most suitable
> option for their needs.
>
> - Username and Password: Basic login credentials, often used with two-factor authentication (2FA) for added security.
> - [Two-Factor Authentication] (2FA): Requires a second verification step, such as a code from an authentication app or SMS.
> - [Personal Access Tokens]: Secure tokens that replace passwords for API access and can be scoped for specific permissions.
> - [SSH Keys]: Cryptographic keys used for secure connections to GitHub repositories.
> - [OAuth Apps]: Allows third-party applications to authenticate users without sharing passwords.
> - [Identity Provider Integration]: For organizations, this method centralizes authentication through an external provider.


[Git Authentication]: <https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github>
[Two-Factor Authentication]: <https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/about-two-factor-authentication>
[Personal Access Tokens]: <https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens>
[SSH Keys]: <https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent>
[OAuth Apps]: <https://docs.github.com/en/apps/oauth-apps/using-oauth-apps>
[Identity Provider Integration]: <https://docs.github.com/en/actions/security-for-github-actions/security-hardening-your-deployments/about-security-hardening-with-openid-connect>
<br>

## List of Commands

| Git Commands | Brief Description |
| ------------ | ----------------- |
| ```git init``` | Initializes a new Git repository in the current directory, creating a .git subdirectory to store repository data. |
| ```git clone``` | Clones an existing repository from a remote server to create a local copy on your computer. It automatically sets up a remote named "origin" pointing back to the original repository. |
| ```git add``` | Adds file changes to the staging area in preparation for committing. This command stages changes to be included in the next commit. |
| ```git commit``` | Records staged changes to the repository, creating a new commit with a message describing the changes. | 
| ```git pull``` | Fetches changes from a remote repository and merges them into the current branch. It's equivalent to running git fetch followed by git merge.|
|```git push``` | Pushes local commits to a remote repository, updating the remote branch with your changes. It's used to share your work with others and synchronize changes between local and remote repositories. |
| ```git status``` | Displays the current state of the repository, including any modified, staged, or untracked files. It provides information about which files are staged for the next commit and which files are not being tracked by Git.|
| ```git log``` | Shows a chronological list of commits in the repository, starting with the most recent. It provides information such as commit hashes, authors, dates, and commit messages. |
| ```git branch``` | Lists all branches in the repository. It also indicates the currently checked out branch with an asterisk (*). |
| ```git checkout``` | Switches to the specified branch, updating the working directory to reflect the state of that branch. It's also used to create new branches by specifying the -b flag followed by the new branch name. |
| ```git merge``` |  Merges changes from the specified branch into the currently checked out branch. It combines the changes made in the specified branch with the changes in the current branch. |
| ```git remote``` |  Lists the remote repositories associated with the current repository. It provides information such as the remote's name and URL. |
| ```git config``` | Configure user information used across all local repositories. |
| ```git diff``` | Show the difference of what has changed but mot staged/ |
| ```git reset``` | clear staging area, rewrite working tree from specific commit point. |
<br>

## Amongst the Git commands, the 4 most commonly used in opionion are:
1. git clone: This command creates a local copy of a remote repository, allowing developers to work on the project offline and make changes. It is crucial for collaboration as it enables team members to access the same codebase easily.
2. git add: This command stages changes made to files, preparing them for a commit. It's an essential step in the workflow, as it allows developers to specify which changes should be included in the next commit, ensuring that only relevant modifications are tracked.
3. git commit: After staging changes with git add, the git commit command saves those changes to the local repository with a descriptive message. This creates a checkpoint in the project's history, making it easy to track progress and revert to previous states if necessary.
4. git push: This command uploads local commits to a remote repository, making them available to other collaborators. It is vital for sharing updates and ensuring that all team members are working with the latest version of the code.

