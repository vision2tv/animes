# add
git add .
git commit -m "adicionando arquivo"
git push

# add 2

git pull origin master --rebase

Depois:

git push origin master





# Primeiro, faça pull com rebase para evitar conflitos
git pull origin master --rebase

# Se ainda assim der erro, force o push
git push origin master --force
