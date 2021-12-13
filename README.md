## Git Cheat Sheet

Summary of Git Commands

### Basic Commands
* `git init` - Initalize local Git repository
* `git add .` - Add all files in and under the current directory to git index, staging them for commit
* `git commit -m "Message"` - Commit changes to local repo with commit message

### Info Commands
* `git status` - Display current status of local working directory/repository
* `git log` - List commit history
* `git log --oneline` - List commit history, compact format

### Branching Commands
* `git branch` - List local git branches
* `git branch newBranch` - Create local branch named 'newBranch'
* `git checkout newBranch` - Change local branch to 'newBranch'
* `git branch -M otherBranch` - Rename the current branch to `otherBranch`

### Remote Commands
* `git remote add origin remoteUrl` - Add alias "origin" for remote repository URL "remoteUrl"
* `git push origin main` - Push locally-commited changes to `main` branch on remote repository
* `git push -u origin main` - Same as above, setting "origin main" as default for subsequent `git push`
