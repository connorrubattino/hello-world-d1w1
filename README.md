# First Repository

This is my very first repository with Coding Temple

### Git Commands
1. `git init` to create a new repository
2. `git add <filename>` or `git add.` to add files to staged changes
3. `git commit -m "YOUR MESSAGE HERE"` to commit(or take a snapshot)
4. `git remote add <remote_name> <remote_url>` to add remote connection to Github
    - `<remote_name>` will usually be `origin`
    - `<remote_url>` is the URL to Github repository
5. `git push <remote_name> <branch_name>` to send commits to Github
    - `<remote_name>` will usually be `origin`
    - `<branch_name>` will usually be `main`
    - You can add `-u` flag to command to set up tracking
6. Create a new branch: `git checkout -b <new_branch_name>`
    -use `git checkout <branch_name>` to switch branches
    -use `git branch` to get a list of existing branches