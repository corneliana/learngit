Git is a distributed version control system.
Git is free software distributed under the GPL.
What are all those things? I literally have no idea.
How can you call this like "Git doesn't see any changes inside your repository, only files outside the repository, which it considers 'untracked' and so ignores when generating a diff"
So what is the problem? Am I too confident or something?
Git has a mutable index called stage. To add a file to Git's repository, add it to the stage first and then commit it to the branch (master) which is automatically created by Git.
Git tracks changes.