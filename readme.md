# Laboratorio Git

## 1. Crear un repositorio en local

- Abre tu terminal y navega hasta el directorio donde deseas crear el repositorio.

```
cd Workspace
cd Lemoncode_Javascript
```

- Crea una carpeta con el nombre del repositorio.

```
mkdir Laboratorio_Git
```

- Ingresa a la carpeta que acabas de crear.

```
cd Laboratorio_Git
```

- Inicializa el repositorio de Git.

```
git init
```

## 2. Subir el repositorio a GitHub

- Crea un nuevo repositorio en GitHub.

    > https://github.com
    >
    > click botón new
    >
    > poner título, readme.md 
    >
    > click botón create repository

- Copia el URL del repositorio que acabas de crear en GitHub

    > copiar SSH

- Conecta tu repositorio local con el repositorio en GitHub.

```
git remote add origin [SSH]
git push -u origin master
```
- Verifica que la conexión se haya establecido correctamente.

    > https://github.com/PacoMateos/Laboratorio_Git

## 3. Hacer un commit y un push

- Crea un archivo en la carpeta del repositorio.
```
git code .
```
  > Crear archivo readme.md
  > Editar archivo readme.md hasta punto primero.

- Añade el archivo al staging.
```
git add .
```

- Crea un commit con un mensaje descriptivo.
```
git commit -m "Primer commit, subiendo Readme.md"
```
- Sube los cambios al repositorio en GitHub.

  > git push -u origin master


