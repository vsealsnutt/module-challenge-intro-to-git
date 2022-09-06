## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is an open source distributed version control system. This means that multiple developers can pull copies of original source code down to their own local computers and make changes to it, and Git will track the content and maintain a history of all changes made.

2. What is the difference between Git and GitHub?
    While Git is a version control system on your local computer that keeps track of your source code history, GitHub is a cloud-based service that can manage Git repositories remotely.

3. Why do we create a branch? 
    We create a branch to make it easier for multiple developers to work on the same project at the same time. When a developer is finished with their branch, it can be merged back into the main code. 

4. What is the purpose of a Pull Request?
    The purpose of a Pull Request is to let your team know that your code changes are ready to be reviewed. A manager or other team members can review the pull request and determine if it is ready to be merged with the main code or if more changes are needed.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
    The command you can use to switch between branches is 'git switch' and the name of the branch you want to switch to.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    Using 'git fetch' from your local repository will show if there are updates in the remote depository. 'git merge' will actually merge the changes from the remote repository into your local repository. 'git pull' is different from 'git fetch' because it will immediately merge changes without letting you review. Merge conflicts are possible when using 'git pull'.

7. What is a merge conflict?
    A merge conflict happens when two develpers make different changes to the same lines of code and commit it, and Git is unable to automatically resolve the differences.

8. How do you resolve a merge conflict?
    To resolve a merge conflict, you have to edit the lines of code that had the conflict. GitHub has a conflict editor that can be used to resolve competing line changes. Otherwise, you have to resolve the merge conflict in your local repository and push the change to your remote branch.
