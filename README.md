# learnable Web3 Task2

1. Explain version control
2. Explain difference between git and github
3. List 3 other alternatives
4. Explain the difference between git fetch and git pull
5. Explian in simple terms git rebase and the command for it
6. Explian in simple terms git cherry-pick and the command for it



# Answers To Tasks

1. Version control

Version control: is a system that records changes to files over time so you can recall specific versions later. It is commonly used in software development to manage changes to source code. It allows:

- Collaboration among multiple developers.

- Tracking changes and who made them.

- Reverting to previous versions if needed.



2. Difference Between Git and GitHub

- Git: A distributed version control system used to track changes in source code. It operates locally on your machine.

- GitHub: A web-based platform that hosts Git repositories. It adds collaboration features like pull requests, issue tracking, and project management tools.




3. 3 Alternatives to GitHub

- GitLab: Similar to GitHub but includes CI/CD tools and can be self-hosted.


- Bitbucket: A Git repository hosting service focused on integration with Atlassian tools like Jira.


- SourceForge: An older platform that offers project hosting for open-source software.





4. Difference Between git fetch and git pull

- git fetch: Downloads changes from a remote repository but does not merge them into your local branch. It's like "checking for updates" without applying them.

- git pull: Combines git fetch and git merge. It downloads changes and merges them into your current branch.




5. Git Rebase

Rebasing means moving or "rebasing" your branch to the tip of another branch. It rewrites commit history to create a linear sequence of commits, making the project history cleaner.

Command:
git rebase <branch-name>

Example: If you are on feature and want to rebase onto main:
git checkout feature
git rebase main




6. Git Cherry-pick
Cherry-picking means applying a specific commit from one branch to another without merging the entire branch.

Command:
git cherry-pick <commit-hash>

Example: If you want to apply a commit with hash develop to your current branch:
git cherry-pick develop