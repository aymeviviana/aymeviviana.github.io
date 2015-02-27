## Tracking Changes Reflection

- How does tracking and adding changes make developer's lives easier?
- What is a commit?
- What does the HEAD^ argument mean?
- What are the 3 stages of a git change and how do you move a file from one to the other?
- Write a handy cheatsheet of the commands you need to commit your changes?
- What is a pull request? Why do you think they are preferred when working with teams?

Tracking and adding changes prepares them (or stages them) to be committed. A commit acts as a "save point" which saves your change in case you ever need to revert back to it. 

The HEAD^ argument refers to the previous commit that was made, while HEAD refers to the current commit you are on. HEAD~3, HEAD~4 & HEAD~5 are the 3rd, 4th and 5th commits from HEAD. 

The three stages of a git change include working, staged and committ. The working stage is when you make a change to a file, the staged stage is when the change has been prepared to be committed, and the commit stage is when a change has officially been saved to the branch. To move a change from working to staged you type 'git add < filename >' in terminal. To move a change from staged to commit you type 'git commit -m "Enter your commit message here" ' or 'git commit -v'.

Commit Commmands Cheat Sheet
- To stage a change for commit: git add < filename >
- To discard changes in working directory: git checkout -- < filename >
- To commit a change the short way: git commit -m "insert commit message here"
- To commit a change the long way: git commit -v
- To change files that were just commited: git reset --soft HEAD^

Pull requests, rather than direct pushes, are preferred when working with a team because it gives the programmer an opportunity to have their code reviewed by a team member before having it pushed live. 