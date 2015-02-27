# Setting Remotes

- What is a remote?
- How are they set up?
- Summarize the purpose of a remote
- Write a brief workflow (list of commands) on how to fetch changes from Dev Bootcamp's master branch

A remote is a URL that tells Git where to go in order to Pull and Push files. Setting up a remote is very easy. The git command is: git remote < insert remote name > < URL > (i.e. git remote origin https://github.com/aymeviviana/phase-0-unit-1). To view all current remotes set up on Git type: git remote -v (the v stands for verbose). You can think of a remote as a map that guides Git to the exact location where the treasure is burried (treasure = push/pull files).

Here's a list of useful git commands to remember when fetching changes from DBC's master branch:
- When fetching from DBC repo: git fetch upstream < branch >
- When merging changes from DBC repo: git merge upstream/< branch >
