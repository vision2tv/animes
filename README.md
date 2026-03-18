git add .
git commit -m "adicionando arquivo"
git push







# Primeiro, faça pull com rebase para evitar conflitos
git pull origin master --rebase

# Se ainda assim der erro, force o push
git push origin master --force
