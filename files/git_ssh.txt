ssh-keygen -t rsa -b 4096 -C "g00u00@outlook.com"
eval $(ssh-agent -s)
ssh-add  ~/.ssh/id_rsa
cat  ~/.ssh/id_rsa.pub
echo "ssh -T git@github.com"
