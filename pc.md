## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is an open source distributed version control system.
2. What is the difference between Git and GitHub?
    GitHub is the company that offers the cloud-based git hosting service. Whereas Git itelf is the system used to modify and redistribute code.
3. Why do we create a branch?
    We create a branch to isolate our work from other team members so that we can work on our section of code without ruining or messing up anyone elses work at the same time.
4. What is the purpose of a Pull Request?
    The purpose of a pull request is to update the local version of a repository from a remote version.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    `git checkout` 'main'
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
   `git fetch` allows you to bring commits, files, and references from a remote repository into your local repository without changing your existing local work. On the other hand, a `git pull` will fetch content from a remote repository and update the local repository to match that content. `git merge` combines branches together integrating the previously forked branch changes back into the branch you forked from, at the same time resolving any conflicting edits made.
7. What is a merge conflict?
    A merge conflict is when 2 people are working on the same file at the same time doing different things, and git is unable to determine which change is correct.
8. How do you resolve a merge conflict?
    To resolve the merge conflict, edit the conflicted file then commit it.