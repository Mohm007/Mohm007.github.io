# Mohm007.github.io

This is change the hostname of our Website(such that it doesnot contain any forbidden characters like "/","%", etc)
For this we need to clone our git repos and at the end push back the repo from local device.
Final URL format which will be obtained from these steps: "<git_username>.github.io"
Example: Mohm007.github.io

1)First create a folder on local device and open git bash in that folder and clone our repos there

--> cd WebOTP_domain/
--> git clone https://github.com/Mohm007/Mohm007.github.io.git

2)Now Mohm007.github.io{<username>.github.io} folder will be create inside WebOTP_domain folder in local
Go inside that Mohm007.github.io folder and type the following commands
Note: Even if code is not present in github, we can copy paste the files from local and push it to github(but it should have index.html file)

--> cd Mohm007.github.io
--> git init
--> git status
--> git add --all
--> git commit -m "Initial Commit"

3)Now push it to origin
--> git push -u origin master
if this command doesn't work, try below command 
--> git push origin main

4)Now try checking the website "Mohm007.github.io", the index.html content will be rendered 


