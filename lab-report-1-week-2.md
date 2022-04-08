# Week 2 Lab Report

### Tyler Lee of the Axolotl Group
A16976522
![Image](axolotl.png)

Note: This tutorial is for Windows Operating Systems.

## Installing VScode
Click on the following link.

[Visual Studio Code](https://code.visualstudio.com)

Click on the blue "Download for Windows" button and save the ".exe" file to your computer's "Downloads" folder.

![Image](VSCode.png)

Run the ".exe" file from your computer's "Downloads" folder and follow the given directions to install VS Code.

## Remotely Connecting

Click on the following link and type in your Username and your Student ID to find your CSE 15L account.

[Link](https://sdacs.ucsd.edu/~icc/index.php)

![Image](account.png)

Open VS Code and simultaneously click "Ctrl + Shift + `" to open a new terminal. Then, type in "ssh cs15lsp22xxx@ieng6.ucsd.edu" (without the quotation marks) where the "xxx" is replaced by your special three characters at the end of your account name.

![Image](login.png)

If the terminal prompts for allowing IP access/trust, just accept the prompt (should just be typing "y" or "yes" and clicking "Enter").

The next prompt will request for a password but you will not see anything when you try entering something. That is fine. Enter your password and click "Enter". If it requests for the password again, it means your password was incorrect so just re-enter your password until it is accepted. Once you login, you should see something similar to the following block of text.

![Image](textblock.png)

## Trying Some Commands

* cd : change directory
* cd .. : go up one directory
* cd ~ : return to home directory
* pwd : print working directory
* ls : list items in the current directory
* ls a : list all items (including hidden items) in the current directory
* cp : copies a file to another location
* rm : remove a file
* cat : prints out the contents of a file

These are some general commands that are useful in many situations. However, more commands and their implementation can be found on many websites online. As an example, here is a link to one such site. 

[Link](https://www.comparitech.com/net-admin/powershell-cheat-sheet/)

## Moving Files with scp

scp : allows for copying files between your local computer and your remote CSE 15L account.

## Setting an SSH Key

## Optimizing Remote Running
