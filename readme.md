Here are some additional steps that I had to take that I did not see in my original instructions:

1. Set Name and email for git as follows:
   
    git config --global user.name "Your Name"

    git config --global user.email "your_email@example.com"
3. Make sure the newline is converted if you are working on Windows:
   (this did not work yet, so I double spaced instead)
   
    git config --global core.autocrlf input
5. First, I staged changes and then did commit and push (to upload changes to github)

The order is:

clone the repository to make a local copy (best is to use a branch)

make your changes locally

save

stage changes

commit 

push
