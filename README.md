
<img width="222" alt="Screen Shot 2024-01-13 at 4 02 07 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/fe3d9957-b7af-4ef8-a056-1a56eb9a24bc">
The working directory is initially /home/lecture1/ when I ran all the commands below.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.) NO ARGUMENTS (cd, ls, cat)

When we pass in no argument for the cd command, the directory doesn't change, and hence, nothing is printed. 

<img width="195" alt="Screen Shot 2024-01-13 at 4 02 32 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/b849d395-7383-4934-a2f5-8c628266d22e">


When we pass in no argument for the ls command, it will just list the folders in the current working directory. As shown in the first picture, the main folder in /home is lecture1. 

<img width="207" alt="Screen Shot 2024-01-13 at 4 13 08 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/e80a846f-5075-48ac-a80b-9825fd14099b">


When we pass in no argument for the cat command, it by default reads from the terminal and so nothing is printed.

<img width="226" alt="Screen Shot 2024-01-14 at 1 05 28 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/6378777a-4047-498c-a2f7-73dcfb7a397f">

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2.) Using the command with a path to a directory as an argument (cd, ls, cat)

   If we pass in /home/lecture1/messages/ as argument for cd command, the directory will shift from /home/lecture1/ to /home/lecture1/messages

<img width="412" alt="Screen Shot 2024-01-13 at 4 31 22 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/61790945-9e56-45ff-967d-da1ff4a1a3e5">

  
  If we pass in /home/lecture1/messages/ as argument for ls command, the names of all the files in messages will be displayed
  
<img width="415" alt="Screen Shot 2024-01-13 at 4 35 52 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/ff9bba2d-1c8d-4d2d-aefc-87e57cc42ab1">


  If we pass in /home/lecture1/messages/ as argument for cat command, 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.) using the command with a path to a file as an argument.

   If we pass in /home/lecture1/README/ as argument for cd command, an error message will be produced. This is because we can't change the directory to a single file.
   
   <img width="483" alt="Screen Shot 2024-01-14 at 12 50 43 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/3b8018c1-0029-46dc-ab5e-62247cb0d4c4">
   

   If we pass in /home/lecture1/README/ as argument for the ls command, an error message will be produced. The ls command can only read all file names in a given directory, but it would not be able to handle a sole
   single file as an input.
   
  <img width="578" alt="Screen Shot 2024-01-14 at 12 52 36 PM" src="https://github.com/mathcsnerd/cse15l-lab-reports/assets/153144074/828899fb-7c60-4e0a-918b-4acfc90e4c94">

  



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.) 
