# Welcome to the course!

This is the `README` for the introductory assignment: Intro to GitHub. If you see this `README`, you have already successfully set up your GitHub account and accepted the assignment - hooray!

# Setup

## Configure Git

1. Login in to the [R Server](https://jupyter1.rc.colorado.edu/) and log in with your identikey (if you get an error you may have to log out of private google accounts).
1. Setup Git:
  - in the menu, select `View` -> `Move Focus To Terminal` or switch manually to the terminal tab
  - execute the following commands (with the proper replacements) to set up your github credentials:
  - `git config --global credential.helper store`
  - `git config --global credential.https://github.com.username YOURGITHUBUSERNAME`
  - `git config --global user.email YOUREMAIL`
  - `git config --global user.name "YOURNAME"`
  - double check that the configuration is all correct by executing `git config --list`

## Clone Repository

1. Click on the green `Code` button at the top of your repository and copy the link (starts with `https://github.com/CUB-Stable...`) to the clipboard.
1. Back on the [R Server](https://jupyter1.rc.colorado.edu/), close any open project by selecting `File` -> `Close Project` from the menu (if this is grayed out, you are not in a project yet)
1. Make sure you are back in the terminal (`View` -> `Move Focus To Terminal`). You can clean your terminal by pressing `control + l`.
1. Type `cd`, then hit `Enter` to move to the top level directory before cloning your repository.
1. Type `git clone ` and paste the copied link from step 1 right after (so it says something along the lines of `git clone https://github.com/......git`), then press `Enter` to execute the commmand (this creates a local copy of your GitHub repository and you should see the new folder in your directory tree in the **Files** tab on the right).
1. Navigate into the new folder in the directory tree and click on the `project.Rproj` file to load the new project (confirm to do so when prompted).

# Assignment

Fill out the questions in the `assignment.md` file and upload an image to the `images` folder (see question 4 instructions).

# Submission

Once you have completed this assignment, submit the link to this repository on canvas.
