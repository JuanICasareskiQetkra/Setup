
# Setup

## Setup global

- Instalar [Node 18.18.2](https://nodejs.org/es)
  1. Despues de instalar Node, abrir la terminal y ejecutar el comando `npm i --global yarn`
- Instalar [Python 3.12](https://www.python.org/downloads/)
  1. Instalar Python, tildando la "Add python.exe to PATH"
    ![instalador python](https://i.imgur.com/Rcr6lsa.png)
- Instalar [Git](https://git-scm.com/downloads)
  1. Abrir la terminal y ejecutar los comandos:
     1. `git config --global user.name "Tu Nombre"`
     2. `git config --global user.email tuemail@qetkra.com`
- Instalar [VSCode](https://code.visualstudio.com/download)
  1. Instalar las extensiones "AWS Toolkit", "Python", "Vue Language Features (Volar)", "JavaScript and TypeScript Nightly"

## Setup Frontend

- Ejecutar los comandos en el root del proyecto:
  1. `yarn`
  2. `quasar dev`

## Setup Backend

- Ejecutar los comandos en el root del proyecto:
  1. `py -m venv env`
  2. `py -m pip install -r requirements.txt`
  3. Uno de los dos siguientes:
     1. De estar usando Powershell `env/Script/activate`
     2. De estar usando otra consola `source env/Script/activate.bat`
  4. `chalice local` para desarollo local
