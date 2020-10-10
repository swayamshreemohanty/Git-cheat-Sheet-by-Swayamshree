# Git-cheat-Sheet-by-Swayamshree
PDF is available for downlaod.

This is the basic command-line for using GIT for beginners. 

1.	To open a new repository in your current working directory using GITBASH	                •git init
2.	To delete the exiting repository in your current working directory using GITBASH	        •git rm -rf .git
3.	To check the GIT status of your current directory  	                                        •git status


4.	To add all your files/folders to the repository. 	                                    •git add <file/folder name>
                                                                                                  (only for single file/folder)
                                                                                                    •git add .
                                                                                                  (for all the files/folders in the directory)
 
5.	To commit your files/folders in the repository. 	                                    •git commit -m “Your message” 
	
  
For working on your project using branch 	
1.	Create a new branch	                                                                    •git branch <branch name>
2.	Go to another branch									    •git checkout <branch name>
3.	Create and go to another branch								    •git checkout -b <branch name>
4.	After modification in your new branch, then commit it with the new branch repository.	    •git commit -a -m “Your message” 
(For add and commit in the new branch directory)
5.	To merge the branch with the MASTER branch. First go to your new branch. Then type: -       •git merge <branch name>
6.	To delete a slave branch, 1st go to the main branch, then type: - 			    •git branch -D <branch name> 


For push your files/folders to GITHUB	
1.	After the above-mentioned process, then go to your GITHUB account and create a blank repository in your GITHUB, then copy your GITHUB repository URL.	

2.	In your working directory, open Git bash
Then create a remote for your repository using the copied link.	                 •git remote add <remote name> <” origin” is used as default name> “your copied URL from GITHUB”
3.	To push the working directory files/folder to your GITHUB	                                  •	git push -u <remote name> <branch name>
                                                                                                  or
                                                                                                •	git push -u “your copied URL from GITHUB” <branch name>

	
For pull your files/folders to GITHUB	
1.	For pull existing repository from GITHUB	                                                  •	git pull -u <remote name/URL name> master
2.	If confits occurred during pulling 	                                                        •	git pull   <remote name/URL name> --allow-unrelated-histories
