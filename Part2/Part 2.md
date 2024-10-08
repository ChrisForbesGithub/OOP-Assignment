# OOP-Assignment
 OOP Knowledge Assignment

 1.	List three major version control software for software engineering.
 Git, Apache and Mercurial.

2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
Git's main advantages include it's branching capabilities, its simplicity, and how commonly its used. It is particularly useful for game development as it allows large, complex
projects to be assembled by a large team of individuals.

3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
Branch - A copy of a project that allows new features to be implemented and tested without the risk of breaking the main branch
Pull - download from an online repository
Push - upload a repository or an update for a repository online
Repository - An online or local folder in which a project is contained
Working Copy - An editable repository copy
Merge - Recombination of a forked development process

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Developing new software or new applications, upgrading software or applications, or debugging/fixing software or applications. 

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
For resolving Git merge conflicts, consider these tools: KDiff3, Meld, P4Merge, Beyond Compare, WinMerge, Araxis Merge, DiffMerge, Visual Studio Code with extensions like GitLens, IntelliJ IDEA, or GitKraken.
These tools enhance the merging and conflict resolution process.

6.	In a merged source code file, how does Git let you know there is a conflict?
The status command will help to identify conflicted files during a merge. When Git detects a merge conflict, it marks the conflicting areas in the source code file using special markers.
The file will show sections enclosed between <<<<<<< HEAD and =======, which indicate the conflicting changes from the current branch.
The incoming changes from the branch being merged are shown between ======= and >>>>>>> branch-name. These markers help you identify and separate the conflicting code.
To resolve the conflict, you need to manually edit the file to integrate the changes, remove the markers, and then stage and commit the resolved file.

7.	What are the steps you can take to resolve Git conflicts?
First the specific conflicting files should be identified. Then, the changes that have been made to those files since the initial branching should be identified. Once the exact issue
is known, edits to the relevant files can be made.

8.	What does git revert do, and how can you use it?
Git's revert command is used for undoing/reverting changes to a repository's commit history.

9.	What does git reset do, and how can you use it? 
Git's reset command undoes changes to an individual working directory and resets it back to a specific commit.

10.	What is the difference between git revert and git reset?
Git revert creates a new commit that undoes changes from a previous commit, preserving history, making it ideal for shared branches.
In contrast, git reset moves the branch pointer to a different commit, altering commit history, with options to keep changes in the working directory, unstage changes, or discard all changes.
Use git revert for safe, history-preserving rollbacks and git reset for modifying or cleaning up local changes.

11.	True or False: It is okay to commit broken code to the main branch.
False. While technically possible, committing broken code to the main branch should be avoided whenever possible.

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True.

13.	Describe what is DevOps, how is it useful for game developers?
DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to enhance collaboration, automate workflows, and improve deployment speed and reliability.
For game developers, DevOps is useful because it streamlines the development pipeline by integrating continuous integration and continuous deployment (CI/CD) practices, automating testing and deployment processes, and facilitating better collaboration between development and operations teams.
This results in faster updates, more reliable game releases, and a more efficient response to player feedback and bug reports.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Tools that can be used with DevOps include Git, which can be used to collaboratively develop a project, Teams, which can be used for professional communication between developers and
operators, and Jira, which can be used for issue tracking, bug tracking and project management.

15.	What is CI/CD and how can it be used to automate the game development process?
CI/CD stands for Continuous Integration and Continuous Deployment.
CI involves automatically integrating code changes from multiple contributors into a shared repository several times a day, followed by automated testing to ensure code quality.
CD extends this by automatically deploying these tested changes to production environments.
In game development, CI/CD automates the build, test, and deployment processes, enabling developers to quickly validate new features, catch bugs early, and release updates more frequently.
This automation enhances efficiency, reduces manual errors, and accelerates the overall development cycle.