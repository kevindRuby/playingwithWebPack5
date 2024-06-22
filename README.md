# My first README

**To create this project repo I did this::**
echo "# My first README" >> README.md
git init
git add README.md
git add .
git commit -m "adding first files"
git branch -M main
git remote add origin https://github.com/kevindRuby/playingwithWebPack5
git push -u origin main

**To add consecutive files e.g. second set etc etc:**
git add .
git commit -m "adding second set of files"
git push -u origin main

**To add just one file if you edited it:**
git add <filename>
git commit -m "<filename>"
git push -u origin main

**To Delete a file from this project repo I did this::**
git rm <file_name>
git commit -m "Deleted <file_name>"
git push

**To pull down changes from the remote repo to my local repo::**
git pull origin main

**Django stuff:**
To Find the Location of Your Django Installation:
Open the Command Prompt at C:\> Type the following command: where python

    Type the following command for the version:      **python --version**

    Checking the Django Version type:    **python -m django --version**

    (OPTIONAL)  To update Django to a newer version, use the following command:  ** pip install --upgrade Django**
