# VS Code Git setup
## Local folders setup
* Create master folder (only once) for all local repositories, ie C:\Repos
## Remote repository setup
* Create new repository at GitHub: https://github.com/
* Click *Clone or download* button and copy the link
## VS Code setup
### Global settings
Enter global username and email in terminal
* git config --global user.name YourUsername
* git config --global user.email youremail@address

and confirm entered settings in terminal

* git config user.name
* git config user.email
### Worspace and repositories
Manage workspace

* File > Add Folder to Workspace... > select C:\Repos folder to add folder to current workspace
* File > Save Worspace As... > save new workspace to name it

Clone repositories into your workspace (in terminal window)

* git clone 'URL from github link copied earlier'
* git clone 'another URL link from github for another repo'
