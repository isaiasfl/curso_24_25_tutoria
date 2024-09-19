# Comandos de git

## Configuración

```bash
# versión de Git
 git --version
 git -v

# en mi directorio base /users/isaias/.gitconfig [en Windows]
  git config --global user.name "isaiasfl"
  git config --global user.email "isaiasfl@gmail.com"
  
# mostrar la configuración almacenada
  git config --list 

```

## Los tres estados en Git

Al usar Git, los archivos de tu proyecto se puede encontrar en uno de los siguientes estados:

- _modificado_ (modified): El archivo contiene cambios pero todavía no han sido marcados para ser confirmados. Se encuentra en el directorio de trabajo.
- _preparado_ (staged): Son los archivos que han sido modificados en el directorio de trabajo y se han marcado como preparados para ser confirmados en el repositorio local. Se encuentran en un área temporal transitoria. Esta acción recibe el nombre de add.
- _confirmado_ (committed): El archivo se encuentra grabado en el repositorio local. Esta acción recibe el nombre de commit

<div style="text-align: center;">
  <img src="./Estados_Git.png" alt="Estados Git" style="width: 60%;"/>
</div>
