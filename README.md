Branch 1 Library management 

 mkdir management
   14  cd management
   15  git init
   16  git status
   17  git add .
   18  git commit -m "library management"
   19  git checkout -b branch1
   20  git status
   21  git status
   22  git add .
   23  git commit -m "Changes in file"
   24  git chcekout master
   25  git checkout master
   26  git merge branch1
   27  echo "This Is library management system" >> README.md
   28  git add .
   29  git commit -m "This is readme file"
   30  git checkout branch1
   31  echo "Branch 1 Library management " >> README.md
   32  git add .
   33  git commit -m "branch 1 readme file"
   34  git checkout master
   35  git merge branch1
   36  git mergetool
   37  git add .
   38  git commit -m "Conflict Resolve"
   39  touch .gitignore
   40  code .gitignore
   41  git add .
   42  git commit -m "gitignore"
   43  ls
   44  git lfs install
   45  git lfs track "*.jpg"
   46  git add .
   47  git commit -m "lfs track file"
   48  git log --oneline
   49  git tag -a v1.0 -m "Release 1" ec5b493
   50  git tag
   51  git remote add origin git@github.com:sujeetsrahate/management.git
   52  git push -u origin main
   53  git push -u origin master
   54  git push -u origin branch1
   55  cd management
   56  git log --oneline
   57  history
