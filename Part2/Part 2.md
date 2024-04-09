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
Repository - An online folder in which a project is contained
Working Copy - An editable repository copy
Merge - Recombination of a forked development process

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
Developing new software or new applications, upgrading software or applications, or debugging/fixing software or applications. 

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
Git has an in-built mergetool, alternatively code made in git can be used, or git diff.

6.	In a merged source code file, how does Git let you know there is a conflict?
The status command will help to identify conflicted files during a merge.

7.	What are the steps you can take to resolve Git conflicts?
First the specific conflicting files should be identified. Then, the changes that have been made to those files since the initial branching should be identified. Once the exact issue
is known, edits to the relevant files can be made.

8.	What does git revert do, and how can you use it?
Git's revert command is used for undoing/reverting changes to a repository's commit history. It is used for undoing changes on a public branch's history.

9.	What does git reset do, and how can you use it? 
Git's reset command undoes changes to an individual working directory and resets it back to a specific commit. It is used for undoing changes on a private branch's history.

10.	What is the difference between git revert and git reset?
While git revert affects the main, public branch, git reset only resets a private branch back to a commit of the public one.

11.	True or False: It is okay to commit broken code to the main branch.
False. While technically possible, committing broken code to the main branch should be avoided whenever possible.

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True.

13.	Describe what is DevOps, how is it useful for game developers?
DevOps, short for Development Operations, is a software development methodology based on collaboration between software development and IT operations.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
Tools that can be used with DevOps include Git, which can be used to collaboratively develop a project, Teams, which can be used for professional communication between developers and
operators, and Jira, which can be used for issue tracking, bug tracking and project management.

15.	What is CI/CD and how can it be used to automate the game development process?
Continuous Integration and Continuous Delivery/Deployment, or CI/CD for short, is a common software development practice in which small changes and updates are made frequently after
the initial release. This means that features that would take too long to be implemented in the first release can still be added.