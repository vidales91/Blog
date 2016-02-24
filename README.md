Mi-primer-repositorio
=====================

Este es un ejemplo de Github

Una vez instalado Github debes configurarlo:

git config --global user.name "Baldo"
git config --global user.mail "xxxx@xxx.com"

Generas tu Public key

ssh-keygen

Despues lees tu llave para copiarla a Github:

cat ~/.ssh/id_rsa.pub

Arrancando tu proyecto:
git init

touch README/crear archivo

git add README/agregas README
git commit -m "tu primer commit"

git push origin master/lo envias a Github