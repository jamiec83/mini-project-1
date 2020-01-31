
### Git commands and terminology

**Repository-**
*is a virtual storegage of your project. It allows you to save versions of your code, which you can access when needed.*

**Clone -**
*git clone is used to create a copy or clone of remote repositories. You pass git clone a repository URL. Git supports a few different network protocols and corresponding URL formats. Once a developer has obtained a working copy, all version control operations are managed through their local repository.*

**Fork -**
*A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project. Mac Windows Linux All. Most commonly,forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.*

**Branch -**
*Branch - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.*

**Commit -**
*A commit, or "revision", is an individual change to a file (or set of files).It's like when you save a file, except with Git, every time you save it, it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.*

**Merge  -**
*Merging takes the changes from one branch (in the same repository or from a
fork), and applies them into another. This often happens as a pull request (which can be thought of as a request to merge), or via the command line. A merge can be done automatically via a pull request via the GitHub web interface if there are no conflicting changes, or can always be done via the command line.*

**Push/Pull -**
*Pushing refers to sending your committed changes to a remote repository, such as a repository hosted on GitHub. For instance, if you change something locally, you'd want to then push those changes so that others may access them.
Pull - refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.*

**Remote-**
*This is the version of something that is hosted on a server, most likely GitHub. It can be connected to local clones so that changes can be synced.*

**Status -**
*A status is a type of status check on GitHub.*

**Master Branch -**
*As you start making commits, you’re given a master branch that points to
the last commit you made. Every time you commit, the master branch pointer moves forward
automatically. (Note) The “master” branch in Git is not a special branch. It is exactly like any other branch.
The only reason nearly every repository has one is that the git init command creates it by default and most people don’t bother to change it.*
