## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is a version control system that allows you to keep track of changes made within repositories and acess backups as needed.
2. What is the difference between Git and GitHub?
    GitHub allows you to upload your local repositories, made through Git, to a cloud based host so that they can be collaborative.
3. Why do we create a branch?
    We make branches to isolate our work from our team members which is good for introducing new features or fixing bugs and allowing multiple people to work on the same code at the same time.
4. What is the purpose of a Pull Request?
    A pull request allows collaborators to see the changes that you've made.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    "git branch" can be used to see what branches exist and then "git checkout" can be used to switch in between them. To create a new branch, you would use "git checkout -b [new branch name]".
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    'git fetch' allows you to download code from a remote repo and get an update on changes that have been made. 
    'git merge' is used to merge one branch with another (typically the master). It is used in GitLab.
    'git pull' both fetches and merges. It combines changes into one tree and updates your local repo from the remote.
7. What is a merge conflict?
    Merges occur when multiple people have changed the same lines in a file, or a file was deleted. 
8. How do you resolve a merge conflict?
    Git will flag the file as being conflicted and the developer will have to fix it to resume the merge. 
