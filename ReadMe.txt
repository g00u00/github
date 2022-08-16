На GitHub
==================
cat > .gitignore
/.ssh/*
/.idea/*
*/__pycache__/*
/venv/*
id_rsa
id_rsa.pub
.viminfo
.bash_history
----------
git rm  -r .cache/*  --cache


==================
В домашнем разделе
==================
ssh-keygen -t rsa -b 4096 -C "g00u00@outlook.com"
eval $(ssh-agent -s)
ssh-add  ~/.ssh/id_rsa
https://github.com/settings/keys
cat  ~/.ssh/id_rsa.pub
ssh -T git@github.com


==================
rm -rf .git
git init
git branch -M main
git remote add origin git@github.com:g00u00/github.git
git pull origin main

==================

git add .
git status
git status --ignored

git checkout
git branch
git branch -M main
git branch -M master main


git config user.name "g00u00"
git config user.email "g00u00@outlook.com"
git config --list

git commit -m "000"
git log
git show 2bc5c8c3ac844f54b972bfa747678562712decf4  - хеш сумма
git push --set-upstream origin main
git checkout branch
git checkout 4d01e010e068910866b4784fd60906f831bc3cbb  -- src/react-app-env.d.ts

======================
apt-get update;

rm -rf *;
rm -rf .*;
----------
cat > pull.sh
----------
rm -rf .git;
git init;
ls -lAF;
git config user.name "g00u00";
git config user.email "g00u00@outlook.com";
git branch -M main;
git branch;
git remote add origin git@github.com:g00u00/tmp.git;
git pull origin main;
git status;
git log;
ls -lAF;
git config --list;

rm package-lock.json


ufw status verbose
ufw disable

sudo apt-get update && sudo apt-get install yarn
yarn install
yarn start
yarn add react-router-dom

yarn build
su npm install -g serve
su yarn global add serve
serve -s build


cat > push.sh
----------
git add .;
git status;
git status --ignored;
git commit -m "000";
git log;
git push --set-upstream origin main;



