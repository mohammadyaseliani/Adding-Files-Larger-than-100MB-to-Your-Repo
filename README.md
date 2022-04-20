# Adding-Files-Larger-than-100MB-to-Your-Repo

First, you have to get your GitHub token. To get your token, go to the path Settings --> Developer settings --> Personal access tokens --> Generate new token. 

**Step 1:** git lfs install

**Step 2:** git init

**Step 3:** git lfs track "file name"

**Step 4:** git add .gitattributes

**Step 5:** git add "file name"

**Step 6:** git remote add origin <url of your repo>
 
**Step 7:** git remote set-url origin https://<Token>@github.com/GitHub Username/<repo>.git
 
**Step 8:** git commit -m "Add files"
 





