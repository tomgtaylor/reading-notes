# What is Git? 

Git is a DVCS that stores data in a file system made up of snapshots. 
Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. 
If the file has not changed, Git only stores a reference to the already-stored identical version of it.

# How to use Git on Windows

**Step 1: Download Git**

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/win

GitHub

Install Git as part of the GitHub for Windows install.

http://windows.github.com

**Step 2: Initial Customization**

After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. 
To change settings, you can repeat these steps.

- Configuration of Variables

An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

- Identity Setting

After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.
Type the following into Terminal or Command Line:

    git config --global user.name "Jane Smith"

    git config --global user.email "example@email.com"
  
To confirm that you have the correct settings, enter the following command:

    git config --global user.name (should return Jane Smith)

    git config --global user.email (should return example@email.com)
  
- Default Text Editor

Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:

    $ git config --global core.editor emacs

*Note: For some editors, you may need to find specific instructions for default configuration.*

[Back to Reading Notes](https://tomgtaylor.github.io/reading-notes)