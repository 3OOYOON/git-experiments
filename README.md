# git-experiments
Lab for Advanced Software Design class

Steps I took Part 1:
    
    1. Cloned repo. 
        - Since I already have Ubuntu on my computer, I only had to use HTTPS to clone the repo using the command git clone 
        - (I did not use the git client).
    
    2. Then I made a new file called "new_file.txt" using vim and saved it
    
    3. I then used git add "name of file" in this case new_file.txt
    
    4. I then tried to use git commit
        - but it got mad at me because it could not authenticate the user
        - I had to follow the instructions written out to me in the terminal to confirm my email
    
    5. I then wrote a commit message for my commit
    
    6. After that, I tried to commit again by typing in my username and password. 
        - However, it told me they don't support password authentication
        - I had to make a passkey on github.com, specifically the classic version
        - I made the passkey expire on June 30, 2025, so I wouldn't have to make a passkey again in the middle of class
    
    7. I tried to commit again, and it asked for my username and password. 
        - I typed in my username, and for my password, I wrote in my passkey I made on github
        - I also saved the passkey locally on my computer because it won't show you the passkey ever again, and I need it to make commits
    
    8. Lastly, I used git push to push my changes to my repository, and I was able to see the new file on the GitHub website for my repository.


Steps I took Part 2:

    1. I first made a new branch called new branch
    
    2. Then I update new_file.txt

    3. When I tried to push my changes, it wouldn't allow me as I was on a new branch
        - Because of this, I had to make the new branch the head/origin branch

    4. I was now able to push my changes and pull from the repo

    5. I used git checkout main switch to switch to the main branch

    6. Then I used git pull origin main to get the updates from new branch

    7. Next, I used git merge master to combine the branch with my main branch

    8. Lastly, I used git push origin main to finalize the changes to the main branch

Steps I took Part 3:

    1. I made a merge conflict by updating new_file.txt on both the GitHub website and on my computer locally
        - because I purposely did not git pull first, my local repository did not have the updates that were already made
        
    2. To resolve this, I had to merge my branches again using git config pull. rebase false
        - then going into the file I had and updating it to resolve the conflict
        
    3. Once I updated the file with the merge conflict, the conflict was resolved.
