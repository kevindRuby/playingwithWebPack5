# playingwithWebPack5
playingwithWebPack5


**To create this project repo I did this**
echo "# bla" >> README.md
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
