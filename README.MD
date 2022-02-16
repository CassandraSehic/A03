This repository is a guide to using Webstorm, Git, and GitHub on a Windows machine.

**Github** is a good thing to know how to use because it keeps track of changes to code and allows multiple people to work on the same documents within a project at a time. If something goes wrong while editing a document, you can revert to a previous version.

**Webstorm** is an IDE that allows the use of **Git** so you can commit and push changes to your repository on GitHub.

How to Start:

1. Make a **GitHub** Account (https://github.com/join)
2. Install **Webstorm** (https://www.jetbrains.com)
3. Install **Git** as a Local Program (https://git-scm.com/downloads)
4. Connect **GitHub** with **Webstorm** 
   1. In **Webstorm** press (Ctrl+Alt+S)
   2. Select Version control "Git"
   3. Enter the path to git.exe
   4. In **Webstorm** press (Ctrl+Alt+S)
   5. Select "Appearance and Behavior", "System Settings", then "Passwords"
   6. Add your **GitHub** password so it is connected to **Webstorm**

How to Create a Repository from **Webstorm**:

1. Select "VCS" from the top bar
2. Choose "Import into Version Control"
3. Choose "Create Git Repository"
4. Give it a name and press OK

How to Import a Repository from **GitHub**:

1. Within Webstorm select "VCS" from the top bar
2. Choose "Checkout from version control"
3. Enter GitHub repository name
4. Enter its local path name

How to Create a **Webstorm** File:

1. In **Webstorm**, choose "File" from the top bar
2. Choose the type of file you want to create.

How to **Push** a **Commit** to Repository:

1. Select "VCS" from the top bar
2. Choose "Git", then "Push"
3. Add comment in text box about commit
4. Press "Commit"
5. The Repository or its changes will now be on **GitHub**

Git Commands and Terms: 

**branch**: branch references a **commit**, it shows you where particular changes were made in reference to others

**clone**: clone duplicates a repository into a new directory

**commit**: commit updates changes made to the current index with a descriptive message of the changes in the repository

**fetch**: fetch takes from other repositories, including their objects

**Git**: 

**GitHub**:

**merge**: merge joins multiple isolated **branches** together

**merge conflict**: conflicts that arise from the **merge** command with different edits cannot be combined

**push**: push updates remote ref and associated objects

**pull**: pull is the same as **fetch** but it also integrates the **repository** or **branch** its pulling from

**remote**: remote manages a set of **repositories**, by itself it will list the existing remotes

**repository**: a .git/ folder inside a project, tracking all history and changes over time