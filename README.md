…or create a new repository on the command line

echo "# django" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:RAHUL9545416/django.git
git push -u origin master
                

…or push an existing repository from the command line

git remote add origin git@github.com:RAHUL9545416/django.git
git branch -M master
git push -u origin master


 git remote set-url origin https://github.com/RAHUL9545416/django.git
