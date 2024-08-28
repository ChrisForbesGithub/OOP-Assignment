# OOP-Assignment
 OOP Knowledge Assignment

Imagine you are working at a game studio, and they want you to help with installing Git. 

1.	Write instructions on installing git on a windows system. Making sure to include
a.	What are the requirements to install Git on a system.
b.	If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.

Since git already comes pre-installed by default on some computers, it would first be useful to check if it is already present in the system in question. Open the Windows Command
Prompt or Git Bash and type in "git version". The terminal application's output will either tell you which version of Git is installed, or will tell you that "git" is an unknown
command, which means it still needs to be installed.
Git is available to download on gitforwindows, a Git website. Navigate to the latest Git for Windows installer and download the latest version. Once the installer has started, follow
the instructions provided by the Git Setup Wizard until the installation has finished. To verify that Git has been installed, open whichever terminal application you selected to use
during the Git installation (either Git Bash of the Windows Command Prompt) and type in "git version".
If any issues are encountered during the installation of Git in the workplace, it would be advisable to contact the workplace's technical support personnel.

2.	Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
a.	List the most important principles/techniques for creating and working with repositories
To effectively manage Git repositories, use clear commit messages, make frequent small commits, and adopt a branching strategy with feature, release, and hotfix branches.
Regularly merge or rebase branches, conduct code reviews, and resolve conflicts promptly. Maintain a .gitignore file, tag releases, and keep repositories clean by removing obsolete branches.
Leverage Git hooks for automation, document workflows, ensure proper security and access controls, and utilize CI/CD pipelines for consistent builds and deployments.

b.	List the most important principles/techniques for creating and working with branches
To manage Git branches effectively, use a consistent branching strategy and create branches for each feature or fix, keeping them short-lived and up-to-date with regular merges or rebases.
Employ descriptive branch names, perform code reviews before merging, and test branches independently.
Resolve conflicts promptly, tag important branches, and delete branches after merging to maintain a clean repository.

3.	List the steps in a Git workflow that the team should follow when working on projects.

First, all the required software for the projects (such as Git) should be installed on all the required devices. Second, it should be decided which type of Git workflow the team
should follow. There are multiple different kinds, including the Feature Branch Workflow, the Forking Workflow, and the Gitflow Workflow. When the most optimal workflow type has been
decided, the steps specific to that workflow should be taken.

For example, In a Feature Branch Workflow, the team should follow these steps to ensure a smooth and organized development process:
1: Create a New Branch: When starting work on a new feature or fix, create a new branch from the main branch. Use a descriptive name for the branch.
2: Develop and Commit Changes: Make changes in the new branch, committing frequently with clear, meaningful messages.
3: Pull Latest Changes from Main: Regularly pull updates from the main branch into your feature branch to stay up-to-date and minimize conflicts.
4: Push Branch to Remote: Push your feature branch to the remote repository to back up your work and allow others to access it.
5: Open a Pull Request (PR): Create a pull request (or merge request) from your feature branch to the main branch on the remote repository platform (e.g., GitHub, GitLab) for review.
6: Review and Address Feedback: Collaborate with team members to review the pull request, address any feedback or required changes, and update the branch as needed.
7: Merge Pull Request: Once the pull request is approved and tests pass, merge the feature branch into the main branch using the platform’s interface.
8: Delete Feature Branch: After merging, delete the feature branch both locally and remotely to keep the repository clean.
9: Pull Latest Main: Pull the latest changes from the main branch to your local repository to keep it updated.