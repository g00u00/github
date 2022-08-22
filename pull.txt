#cat > pull.sh
#vim pull.sh
#bash pull,sh
#rm -rf *;
#rm -rf .*;
#rm -rf .git;
git init;
ls -lAF;
git config user.name "g00u00";
git config user.email "g00u00@outlook.com";
git branch -M main;
git branch;

#git remote add origin git@github.com:g00u00/github.git;
#git config --list;
git pull origin main;
git status;
git status --ignored;
ls -lAF;
git log -n4 --oneline --graph --all;

echo "# a" >> README.tmp;
git status;
git add .;
git status;
git status --ignored;
git commit -m'add README.tmp';
git status;
git status --ignored;


rm README.tmp
git status;
git add .;
git status;
git status --ignored;
git commit -m'rm README.tmp';
git status;
git status --ignored;

git log -n2 --oneline --graph --all;

echo "git reflog --all"
git reflog --all
#git cat-file -p 546fcd1
#rm -rf .git;
