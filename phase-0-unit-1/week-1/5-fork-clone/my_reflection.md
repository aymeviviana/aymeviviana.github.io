## 2. GitHub Introduction Reflection

### From GitHub Introduction Challenge

Git and GitHub, are not the same thing and the two terms should not be used interchangeably. Git lives locally on your computer and is focused on version control while GitHub lives remotely (on the web) and acts as a repository for programmers to share their code remotely and collaborate on projects more easily. 

For example, if two different people are editing an article at the same time, Git would be like the notes & feedback the editors write directly on the article. Git keeps track of every change made to the project. When both editors are done making their changes they realize it would have been easier if they had collaborated by making their changes on the exact same document rather than doing it on separate documents and now having to merge all changes together onto a new, third document. That’s where GitHub comes in. GitHub acts as that central place where all changes, from all collaborators are stored. This way there’s always one version of the project that keeps track of all incoming changes from all collaborators. 

Developers use version control because projects are often worked on by a team of programmers, and when multiple people are working on a project at the same time you need a reliable system for keeping track of and incorporating everyone’s changes into the main project without overriding anyone’s individual changes. In general, it makes sense to use version control because you don’t want to end up with 10 slightly different versions of the same website or application, you want to end up with one final version that incorporates everyone’s edits. 

What doesn’t make sense to me at this point is some of the terminology. For example, I understand what it means to push your code, but I’m not super clear on what “pulling” code means?


### From Fork and Clone challenge

To fork a repo (repository)
- Navigate to the GitHub repository you want to fork
- Click the "Fork" button on the top right of the repo page
- Select your username
- Navigate to your Profile page and click the "Repositories" tab, there you'll see your forked repo.

To clone a repo onto your local machine...
- Copy the HTTPS clone URL on the bottom right of the repo you want to clone
- Open up Terminal and navigate the directory where you want to put your clone
- Type this into terminal: git clone < insert the HTTPS clone URL > and press enter
- Run ls on your current directory to confirm that the repo was cloned
- Check your remotes by typing: git remote -v
- Add a remote by typing: git remote add <name of remote> <HTTPS clone URL>

At first I struggled to understand that forking and cloning are two different things. They both make a copy of a GitHub repository but forking places that copy inside your github account while cloning creates a copy on your local machine. It clicked once I did the entire process by myself without following the video. 


<!-- Add your reflection here. Remove the comment markers -->
