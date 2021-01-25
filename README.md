# GitHub Basics 01

## Objective

1. Create a GitHub account
2. Interact with GitHub Repositories

## Tech Requirements

* Terminal
* Web Browser
* Git

## Activity 1 - GitHub User

1. Go to [GitHub.com](https://github.com/) and create an account
2. Complete this [form](https://docs.google.com/forms/d/e/1FAIpQLSfKaOTl9Lv3k92gBy4a6TN9dUa426ymCJI3kflKp37P7XyXoQ/viewform?usp=sf_link)

## Activity 2 - A New Repo

### Activity 2a

1. Work in groups of 2-4. Each member should have their own work
2. Using Terminal, navigate to your projects folder
1. Create a new folder called 'first-github-repo'
2. Change directory into 'first-github-repo'
3. Initialize a new Repository with `git init`
4. Create an html file with `touch index.html`. Add and Commit this new file.
4. Go to [GitHub.com](https://github.com/) and login
5. In the top right corner of the screen, click the plus(+) icon and select new repository
6. On the 'Create a new repository', input 'first-github-repo' as the repository name. Also, make sure 'Public' is selected
7. Click 'Create repository'
8. This will take you to a screen with examples of next steps to take. Copy the code from under the section '…or push an existing repository from the command line'
9. Return to terminal and paste the code from the previous step. Then, press enter
10. Go Back to the GitHub webpage and refresh the page

### Activity 2b

1. Using a code editor, open 'index.html` and add the global structure
2. Add and commit the changes
3. Use `git push` to update the GitHub repository with your local changes
4. Create a heading for you page
5. Add and commit the changes
6. Use `git push` to update GitHub
7. Go to GitHub.com and view the updates to the repository

## Activity 3 - Fork and Clone

Each group member will take turns updating the repository

1. Choose a group member to go first
2. The first member should:
	1. In the web browser navigate to [this link](https://github.com/code-differently/my-first-git-project). Notice in the top left it displays 'code-differently/my-first-git-project'. This is a code differently repository.
	2. In the upper right corner you will find a button labeled 'fork', click it. This will now create a copy of this repository and put it into your account. Notice the top left corner of the page. Now it has your user name.
	3. Just below your user name and the name of the repository, you will find a horizontal list of links. Choose 'Settings'
	4. In the left side navigation you will find a button for 'Manage Access', click it
	5. Now on the right you see a section labeled 'Manage Acces', click the green 'Invite a collaborator'. This will allow you to git access to other developers to work on the repository with you.
	6. Add your team mates as collaborators. The will need to confirm using the email that is sent to them.
3. Each team member should:
	4. 	Navigate to this repository on github.com. 
	5. In the right of the page, they will find a green button labeled 'code', 
	6. select this and copy the address under 'HTTPS'.
	7. In Terminal, navigate to the folder that has all your projects and type `git clone <the-copied-address-from-github>'. This will clone the repository to the local machine
9. A second team member should:
	1. Open a code editor.
	2. Open the folder that was just created in their class projects folder.
	3. Open the index.html file.
	4. Create an `h1` tag and enter a team name for the group
	5. Use git to add and commit the changes
	6. Use `git push` to push the changes to the github repository
10. Each team member should:
	1. Verify that they are in the 'my-first-git-project` directory.
	2. Use `git pull` to pull down the changes made to the remote github repository. Do you see the changes?
11. Choose another team member to go next. This team member should:
	1. Add a <ul> tag to index.html with each team member as list items.
	2. With Git, add and commit the changes
	3. Push the changes to GitHub
12. Each team member should pull the changes from GitHub.
13. Continue this process of modifing the index.html file and pushing/pulling the changes to/from github until all members have done the exercise.
