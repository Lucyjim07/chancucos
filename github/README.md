# Como crear un proyecto de GitHub

- Prerequisito. tener una cuenta en Github.

1. Ir a **Repositories** y crear un proyecto nuevo con el botón **New**
2. Ponerle un nombre al nuevo repositorio y modificar las opciones si lo ve conveniente
3. Dar click al botón **Create repository**
4. Github va a dar unas instrucciones con las que se puede vincular el repositorio remoto (el de internet 🌐) con el repositorio local (el del computado 💻)

```bash
echo "# nombre_proyecto" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Lucyjim07/nombre_proyecto.git
git push -u origin main
```

5. Hacer cambios en el proyecto
6. Seleccionar los cambios que queremos respaldar con el sistema de control de versiones.
   6.1 A través de la linea de comandos

```bash
# para revisar el estado de los archivos sin respaldar
git status

# para agregar todos los archivos que se quieren respaldar
git add .
```

    6.2 A tarvés de la herramienta de visual studio code para el manejo de git
    6.2.1 Agregamos los archivos que se quieren respaldar
    6.2.2 Colocar un mensaje explicando los cambios realizados
    6.2.3 Crear el commit y hacer push con el botón de la herramienta
