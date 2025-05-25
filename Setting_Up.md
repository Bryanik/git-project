# Setting Up
- cd into `git-project`
- Configure git:
    - Username: `git config --global user.username 'yourUsername'` <!-- Note: yourUsername in quotes -->
    - Email: `git config --global user.email myEmail@gmail.com` <!-- Note: No quotes for email -->
- To view configurations use `git config --list`
    <!--! Important -->
    - When you run `git config --list`, the output may open in a pager like `less` if it's long. This lets you scroll, but you'll need to exit the pager to return to the command line.
    - To escape / exit, press `q` or `:q`
    - If you just want the output printed directly to the terminal without entering the pager, use `git --no-pager config --list`
- Convert the folder/project to a git repo with `git init`
- Create a new file called 'app.js' with `touch app.js`
- Add some lines of code to `app.js`
- Stage the changes to be sent to git with `git add fileName` or `git add .` to stage all files
- To check if there are any unstaged changes made on the application, use `git status` 
- The next step is to commit the changes before they are pushed to github to be hosted, using `git commit -m 'Any Descriptive Commit Message'`
