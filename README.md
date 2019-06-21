In order to add docs to your Repo through Terminal

Step 1: Make a local directory

        example : mkdir test
        
Step 2: Chnage your current working directory location to this newly made directory
  
        cd test/
        
Step 3: Create new file which you want to upload in this directory

        gedit test.txt &
        
   ---- Also Create a README.md file        
      
        gedit README.md &
        

Step 4 : Now initialize the git locally using the command
  
         git init
        
Step 5:  We can check the status of this git using
        
         git status
         
Step 6: Now we can add these file to git locally 

        git add README.md
        git add test.txt
        
Step 7: Config your git

        git config user.email "enter your email here"
        git config user.name "enter your user name here"
        
Step 8: Now you are ready to make your first Commit through terminal
  
        git commit -m "first commit"
        
Step 9 : Now bind your local repo to the actual git on web
    
        git remote add origin https://github.com/bhrt-sharma/test.git

Step 10 : Final step is to push this local repo to the binded repo on web
  
        git push -u origin master

        -- You will be promted to provide your UserName
        -- and finally your Password 
