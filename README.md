# Using Unity with Github and Github LFS

## First of All What Is Github?
<iframe width="560" height="315" src="https://www.youtube.com/embed/w3jLJU7DT5E" frameborder="0" allowfullscreen></iframe>

## Second, What is Github LFS?
Because in Game Development we use large assets we need Large File Storage
<iframe width="560" height="315" src="https://www.youtube.com/embed/_11d1ZsEZ8g" frameborder="0" allowfullscreen></iframe>


## Team Member Setup Instructions

* Open an [Github account](https://education.github.com/)
* Download GitHub desktop [Click Here](https://desktop.github.com/)
* Install Git LFS (goto Install Git LFS Section)
* Share GitHub Username with Team Leader
* Leader will send email invite to you, click view invitation
* This takes you to GitHub Repo (Repository) where the project files reside
* Go to green "Clone Or Download" button
* Click "Open In Desktop"
* Choose where you will save (Clone) this project folder (Don't Change folder name!)
* Click "Clone"
* GitHub Desktop then opens
* Click "Sync" (Top Right) to update project
* Open Unity, go to folder where project was cloned
* Select, and open 
* You can now edit the project

## Using GitHub

* When making changes to the project/game, keep GitHub desktop and GitHub web open
* Whenver you save (should be very regularly), go to GitHub desktop, and put a summary in the "Changes" of what you have done
* Click "Commit To Master"
* Click "Sync"
* Not only will you have pushed up your changes, but you will also have recieved all the changes everyone else has made

## Team Leader Instructions

Install Git LFS (goto Install Git LFS Section)

Create Unity project

Go to Edit → Project Settings → Editor
Change Version Control Mode to Visible Meta Files
Change Asset Serialization Mode to Force Text

Save Project and Scene

Goto Github Desktop and 

Click Add
Chose Project Folders
Click create a repository
Click create a repository again

** Important **

* Goto "Visual Studio Code"
* Goto File Open Folder then Goto Project Folder
* Copy OVER the .gitattributes file in [this repo](https://raw.githubusercontent.com/jazzymcgee/unity-github-setup/master/.gitattributes) into the project folders from the Github repo in RAW
* Copy OVER the .gitignore files in [this repo](https://raw.githubusercontent.com/jazzymcgee/unity-github-setup/master/.gitignore) into the project folder from the Githuyb repo in RAW

* Now Enter Summary "First Commit" then Commit
* Click Publish making sure you have click your account

* Add Colloborators under Settings in the Github repo of your project






## Install GIT LFS

Windows Users:
* goto [Click Here](https://git-lfs.github.com/)
* Download GitBash [Click Here](https://git-for-windows.github.io/)
* Goto GitBash and type `git lfs install` and press enter

Mac Users:
* goto [Click Here](https://git-lfs.github.com/) 
* Goto Terminal and type `brew install git-lfs` and press enter







## Show Hidden Files in Windows 10

1. Goto Control Panel
2. Search File Explorer Options
3. Click "File Explorer Options"
4. Open View Tab
5. Goto "Hidden Files and Folders"
6. Tick "Show hidden files,folders and drives"
7. Click Apply and OK

