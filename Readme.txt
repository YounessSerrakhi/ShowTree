Welcome to the "showTree" bash script for file tree display!




This script allows you to visualize the tree structure of your files in a clear way
and aesthetic. You can customize the display with the following options:

-c: Enable this option to highlight folders and files using different colors.

-i: activate this option to display icons in front of each file or folder, in order to better identify them.

-m: activate this option to display the list of images found with the possibility of displaying them by selecting them.

-h: enable this option to display a list of options you can use

level: specify the depth level of the tree you want to display. For example, if you specify
"level=2", only the first and second level folders and files will be displayed.





To use this script, just run the following command:

./showTree -[options]... [folder_path] [level]





Example :

./showTree -ci /home/user/documents 2

This command will display the tree of folders and files contained in /home/user/documents
using colors and icons, and limiting the display to the first and second level





Dependencies
This script requires fim commands to work properly. Make sure you have them installed before running the script.





author & director
This script was created by:

[SERRAKHI YOUNESS] & [ELBCIR ABDELHADI].
