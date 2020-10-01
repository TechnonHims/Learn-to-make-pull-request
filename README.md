# Learn-to-make-pull-request
The motive of this repo is to make you comfortable in making your first commit and PR.

1. Fork this repo (short form of repository), using the fork symbol ![picture](https://user-images.githubusercontent.com/3686790/61156320-bf9d1480-a4fb-11e9-91d2-68310af16671.png =25x25) on the right up corner.
    Above action will add this repo to your github account.
    
1.1 You can star this repo as well in order to follow the updates and help other community members.

2. Now you just have to copy the url generated using ctrl+h command.
   It will be somthing like : 
   
3. Now open terminal in your system.
   Now change the current directory to 'Desktop' using cd command.
   
4. In the terminal write :
    git clone 
    the above action will copy the whole directory into your local system.
    
5. Currently you are in main branch, you have to make a new branch:
    use command : git checkout -b <new_branch_name>
    Now you will be taken to a new branch, where you can make changes in the repo you have cloned.
    
6. Add your name to Contributers.md file, wherever you wish (preferrably on the top).

7. Now Add an image of any place which you like the most in the Memories folder.

8. Write the name of the places in the Landmark folder.
    You can do the above two processes either manually by cut paste #or
    you can use cd command on terminal to mive to the directory in which you need to make changes, then
    add those changes in the directory using : cp <path of file to copy> ~/Desktop/Learn-to-make-pull-request/<dir_name>
    
 9. After making all changes, just add all the files on the staging area using : 
    git add --all
    
 10. Now check the status of your branch that what are the changes you have made and if you need anything to review.
     This is a very important step before commiting to any repo, just to ensure that everytinh is right.
     
  11. Now you have to make the commit using :
      git commit -m "I, <your_name> have made my first commit"
      Now you are ready to push the changes made to this repo.
      
  12. To push write : git push origin <new_branch_name>
  
  13. Go to your github page in the browser and click on "compare and merge"  option mentioned in green tab.
  
  14. Write any comment you want related to changes you have made and finally click on commit.
  
  15. Now just wait for few minutes before you get a confirmation on making your first pull request(PR).
  
      # Congratulations you have made your first PR and you can do it on other repo as well.
        You can make four PR in order to get cool goodies and a (#hacktoberfest)(https://hacktoberfest.digitalocean.com/) T-shirt from [@digitalocean](https://www.digitalocean.com/)
