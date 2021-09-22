## Gitignore for Windows
------------------

I tried setting up a .gitignore file for one of my Git projects in Windows by right clicking in the main folder (where the .git folder resides) and created a new text document called .gitignore. After typing in the folders I wanted to ignore, those folders still showed up when I did "git add .". 

After some googling, the issue was that the .gitingore had the .txt extension whereas Git requires it to have no extension. The solution was to create a new text document as before but I had to go to "Save As", type filename as .gitignore and change the file type to "All Files" in the drop-down menu.

This did the trick! To verify that the file type was indeed different, I checked the .gitignore file properties and it said " Text Document (.gitignore)" as opposed to " Text Document (.txt)".

Source:
[1](https://stackoverflow.com/questions/36732119/how-to-setup-gitignore-for-windows)
[2](https://stackoverflow.com/questions/343646/ignoring-directories-in-git-repositories-on-windows)