# Comandos útiles de Git

1. git init
2. git add .        <!--agrega los archivos desde el ultimo commit-->    
3. git reset .      <!--revierte lo que hace el git add-->
4. git commit       <!--tomo la fotografía-->
5. git checkout -- . <!--reconstruye archivos a como estaban en el ultimo commit-->
6. git log             <!--ver listado de los commits-->
7. git commit --amend  <!--para arreglar el ultimo commit, -> i -> modifico -> ESC -> :wq! -> ENTER -->
8. git checkout -b rama-heroes <!--crear una rama para evitar trabajar en el master-->
9. git checkout master <!--me voy a rama en este caso master-->
10. git branch -d rama-heroes <!--para borrar una rama-->
11. git push
12. git commit -am     <!--Con esto escribimos de manera simultánea git add y git commit. Cuando git ya le esta dando seguimiento. a(agregar),m(mensaje)-->

13. git pull <!--compara archivos que tenemos en github y los va a traer a nuetros archivos locales-->
14. git fetch <!--detecta si se hizo lgun cambio local o en la nube y lo va a comparar y enviar; los va a dejar igualitos. Podriampos trabajar direct. en la nube y luego sincronizar al local-->
15. git tag <!--para hacer versiones de proyecto. git tag version1.0 -m "version 1.0 de mi proyecto x"   <- vemos nombre y despues descripcion del proyecto-->
16. git log --oneline <!--visualizar el tag-->
17. git push --tags  <!--para subir las versiones-->
