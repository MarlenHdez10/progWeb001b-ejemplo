# Configuraciòn de la cuenta

## Configuracio  inicial
```bash

git config --global user.name "marlenhernandez"
git config --global user.email "hege050910@gs.utm.mx"
git config --list
```

## Creacion del repo en github
```bash
git init
ayuda: Usando 'master' como el nombre de la rama inicial. Este nombre de rama predeterminado
ayuda: está sujeto a cambios. Para configurar el nombre de la rama inicial para usar en todos
ayuda: de sus nuevos repositorios, reprimiendo esta advertencia, llama a:
ayuda: 
ayuda:  git config --global init.defaultBranch <nombre>
ayuda: 
ayuda: Los nombres comúnmente elegidos en lugar de 'master' son 'main', 'trunk' y
ayuda: 'development'. Se puede cambiar el nombre de la rama recién creada mediante este comando:
ayuda: 
ayuda:  git branch -m <nombre>
Inicializado repositorio Git vacío en /home/salas/wireframe/.git/
```

## Se agrega el archivo README.md al repositorio



## Subiendo màs archivos
```bash
git add <nombre archivo>
```

## Sube todos los archivos en la carpeta acual
```bash
git add

```
## Despues de subir los archivos al àrea de stage, se deben etiquetar
```bash
git add index.html
git add README.md
git commit -m "Index primera version"
git push
```
