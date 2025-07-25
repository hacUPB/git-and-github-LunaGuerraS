# Como crear un repositorio remoto en GitHub y rencronizarlo con el repositorio local.

1) Entrar a github.com, iniciar seción y crear un repositorio con un nombre, una descripción y crearlo.

2) Al crearlo se generará un URL, este hay que copiarlo

3) Dentro de Git Bash escribir el comando
    git remote add origin
    Y pegar la URL del repositorio remoto

4) Ya con esto se usa el comando
    git push -u origin
    Para subir el repositorio y enlazar el local con el remoto.

**Listo ya esta creado un repositorio remoto y enlazado con el local**
