# Clone a repository:
Clone this repository to your computer via the CLI (cmd or terminal):
* Open the CLI
* Move to a folder where you want to clone the repo (it will automatically create a folder with the name of the repo):
  You probably need these commands:
  * cd ..
  * cd *name_of_subfolder*
  * git clone *url*
  
* Once cloned, you can open the folder in your IDE (e.g. Webstorm) and start working on the code

# Commit changes:
* Commit your changes in the terminal with the following commands:
  * git status
    * shows the status of the local repository (on your computer)
  * git add .
    * adds all files in the current folder to the commit, including NEW ones
  * git commit -m "Description of your changes."
    * create the commit with a label (message) into the local repository (on your computer)
  * git push
    * push the commit to the remote repository (GitHub)
  * git pull
    * pull the latest changes from the remote repository (GitHub) to your local repository
