# Recyclebin
Unix recyclebin and restore
Unix does not have recycle and restor commands. This project provides recycle and restore scripts for Unix. 
A folder with name recyclebin is created on Home directory.  A hidden file with name .restore.info stores all information about files that are moved to the recyclebin. By using store, the files are restored to their original address.
Options are also available for recycle as follows: 
-i provides and interactive prompt and asks if the user is sure to send the file to recyclebin. 
-v shows a message that indicates the result of recycling
-r recursively recycle all files in a directory and all of its subdirectories
