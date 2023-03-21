## Create an Initial Repository

Use the command in the terminal `git init` YOU MUST BE IN THE DIRECTORY YOU ARE WANTING TO TRACK (You will only need to perform this once.  Never for existing Repositories.)

- In VS Code you can right click the folder you want to start tracking and choose `Open in Intergrated Terminal`


## List all the changes that Git is tracking
Use the command in the terminal of `git status`

## Adding files to the Staging Area

Use the command in the terminal: `git add .`

## Commiting our changes and adding a message

Use the command in the terminal `git commit -m "YOUR MESSAGE HERE" `

## Setting username and email in git
`git config --global user.name "IzzyCraze365" ` sets the username

`git config --global user.email "johnaisabella3@gmail.com" ` sets the user email

`git config --list` will allow you to verify your git settings

# Github
1. Creat a repository and give it a unique name.
2. Copy the last option and paste it into the terminal.

# Already have a repo or a github repo and you want to update with changes.

1. `git add .`
2. `git status` - to verify (optional)
3. `git commit -m "ADD NEW MESSAGE HERE" ` - Ex of messages "added styling" or "fixed bug"
4. `git push origin main`