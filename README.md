# github-tutorial
# This repo is for the CE7 Module 3.2 assignment


```What is GitHub Authentication and how what methods available to be implemented?```

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
