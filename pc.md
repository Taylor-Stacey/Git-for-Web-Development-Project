## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

2. What is the difference between Git and GitHub?
Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then GitHub is designed to help you better manage them.

3. Why do we create a branch?
In Git, branches are a part of your everyday development process. Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.

4. What is the purpose of a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
The easiest way to switch branch on Git is to use the “git checkout” command and specify the name of the branch you want to switch to.
    EX: $ git checkout <existing_branch>
        $ git checkout -b <new_branch>

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
'git fetch' would allow you to compare your repository to another. 'git merge' would push your repository back to the main. 'git pull' would copy the repository for up to date changes

7. What is a merge conflict?
Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.

8. How do you resolve a merge conflict?
You can merge the branches on the command line or push your changes to your remote repository on GitHub and merge your changes in a pull request.!
