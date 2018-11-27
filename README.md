**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
git reset --hard HEAD~1 para no mantener los cambios en la working copy

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
git reset --hard <identificador del commit>

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No, la rama styled ya tenía los commit de la rama master, por lo que no realizó el merge

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Sí, porque había cambios en las mismas líneas del archivo git-nuestro.md de ambas ramas

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?** 
No, fue un merge fast forward, no causó conflicto porque los cambios que tenían ambos 
archivos se realizaron en líneas distintas

**¿Qué comando o comandos utilizaste en el paso 25?**
git graph, es un alias que engloba los siguientes comandos: git log --graph --decorate --pretty=oneline

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?** 
Sí, porque ambas ramas forman una lista

**¿Qué comando o comandos utilizaste en el paso 27?**
git reset HEAD~1

**¿Qué comando o comandos utilizaste en el paso 28?**
git checkout -- git-nuestro.md

**¿Qué comando o comandos utilizaste en el paso 29?**
git branch -D title 

**¿Qué comando o comandos utilizaste en el paso 30?**
git reset —hard <identificador del commit>

**¿Qué comando o comandos usaste en el paso 32?** 
git reset --hard <identificador del commit inicial>

**¿Qué comando o comandos usaste en el punto 33?**
git reset —hard <identificador del commit>

