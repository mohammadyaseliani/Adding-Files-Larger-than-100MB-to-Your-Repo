# Adding-Files-Larger-than-100MB-to-Your-Repo

First, you have to get your GitHub access token. To get your token, go to the path: Settings --> Developer settings --> Personal access tokens --> Generate new token. Now, put the files you want to upload in a folder in your desktop, go to Command Prompt, navigate to the folder path, and follow these steps:

**Step 1:** git lfs install

**Step 2:** git init

**Step 3:** git lfs track "file name" (you can use "*.fileformat" to track all files of the same format)

**Step 4:** git add .gitattributes

**Step 5:** git add "file name"

**Step 6:** git remote add origin <url of your repo>
 
**Step 7:** git remote set-url origin https://<Token>@github.com/GitHub Username/<repo>.git
 
**Step 8:** git commit -m "Add files"
 
**Step 9:** git push origin master

 Wait until the files are uploaded to your GitHub Repository and the process is completed.




