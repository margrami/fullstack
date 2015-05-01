#####
# fullstack
#####

###create a new repository
echo # fullstack >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/margrami/fullstack.git
git push -u origin master

### push a existing repository
git remote add origin https://github.com/margrami/fullstack.git
git push -u origin master
