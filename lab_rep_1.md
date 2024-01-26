
<img width="222" alt="Screen Shot 2024-01-13 at 4 02 07 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/fe3d9957-b7af-4ef8-a056-1a56eb9a24bc">
The working directory is initially /home when I ran ALL the commands below.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.) NO ARGUMENTS (cd, ls, cat)

When we pass in no argument for the cd command, it exists outs of all the sub-directories and ends up in the home directory. In this case, we are already in the home directory and so nothing changes, and hence, nothing is printed (NO ERROR!)

![Image](cd_blankargs)


When we pass in no argument for the ls command, it will just list the folders in the current working directory. As shown in the first picture, the main folder in /home is lecture1. (NO ERROR!)

![Image](ls_blankargs)


When we pass in no argument for the cat command, it by default reads from the terminal and so nothing is printed. (NO ERROR!)

![Image](cat_blankargs)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2.) Using the command with a path to a directory as an argument (cd, ls, cat)

   If we pass in /home/lecture1/messages/ as argument for cd command, the directory will shift from /home/lecture1/ to /home/lecture1/messages/ (NO ERROR!)

![Image](cd_DirectoryArgs)

  
  If we pass in /home/lecture1/messages/ as argument for ls command, the names of all the files in messages will be displayed (NO ERROR!)
  
![Image](ls_DirectoryArgs)


  If we pass in /home/lecture1/messages/ as argument for cat command, an error message will be produced. The cat command is designed to read a file or file interface, so using the directory as an argument will result in an error message

![Image](cat_DirectoryArgs)


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.) using the command with a path to a file as an argument.

   If we pass in /home/lecture1/README as argument for cd command, an error message will be produced. This is because we can't change the directory to a single file. 

   
![Image](cd_fileArgs)


   If we pass in /home/lecture1/README as argument for the ls command, it will just read that file name and display the absolute path. (NO ERROR!)

![Image](ls_fileArgs)
  

  If we pass in /home/lecture1/README as argument for the cat command, we will receive information about the README file. (NO ERROR!)

![Image](cat_fileArgs)




----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
