Crismely Marte

# Homework: 4  The Linux Filesystem

1. **Explain the difference between absolute path and relative path:**
   
Absolute Path always states the entire pathname including the root and the entire pathname to locate a certain file. While relative path shows the pathname to locate a file but that pathname starts from the current working directory. In other words, it starts from the relative like the closest working directory to show you the path to another directory instead of starting from the root.

Example Absolute Path /home/cmarte/CIS-106/HomeWork
Example Relative Path /CIS-106/HomeWork

1. **Why Linux uses / instead of \ for its directory paths?**

Linux uses the / because it is following the UNIX tradition.


3. **In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?**

Linux is cares about case sensitivity which means that unlike Windows, Linux would consider File FILE file and FiLE to be different based on the difference in capitalization. 

4. **What is the Filesystem Hierarchy Standard (FHS) and who maintains it?**
The FHS defines the directory structure and layout of the filesystem and it is maintained by the Linux Foundation 

5. **Explain what type of files are stored in the following directories:**

Directory | What is it used for?
--------- | --------------------
/bin    | Binary files, Programs or Apps and basic Functions
/dev    | Device Files, Hardware 
/etc    | Configuration Files are stored here
/home   | Files for the current USER. Each user have their own Home folder
/lib    | Library Files-Apps uses these files to perform certain functions
/opt    | Manually Installed Software is located here
/tmp    | Where temporary files are stored just in case the app crashes
/var    | (Variable Directory) Contain files and directory that will eventually grow in size as the system continues to be in use
/proc   | Contain Sudo Files which contain info of System process 
/usr    | Where apps that are used by the user are stored

6. **How does a period at the beginning of a file name means (example .bashrc)?**
A period at the beginning of a file name means that it is a hidden file.

7. **Which command would you use to list all the files inside the /usr/share/ directory?**
ls command, which is used for listing al the content of a directory.


8. **If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?**
The cd command by it self will take you directly to home.

9.  **Explain what these commands do:**

`cd .config/.htop; cd ../; ls -lX`
The cd.config/.htop will change set your current directory to be that same patter so you will be located in the .config/.htop.

Then the cd../ will change your directory from .config/.htop tp .config/ 

Then the ls -lX will give a long list of the current directory with -l using long listing format and -X sorting alphabetically by entry extension

10. **John has a lot of files in the directory /var/www/html/webapp. He wants to long list all the files, including hidden files, by modification time (newest first), and with human-readable file sizes. Which command should he use conjuring that his current working directory is:** 
    
`/home/john/.git/`
 cd ../../../var/www/html/webapp; ls -aht