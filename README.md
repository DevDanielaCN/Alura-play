
# Plataforma de gestión de videos (Alura Play)

Este proyecto consiste en el desarrollo de una plataforma web para la gestión de videos, donde se utiliza Node.js para levantar un servidor de desarrollo y JSON Server para simular una API local. La plataforma permite a los usuarios subir videos, los cuales son almacenados en un archivo JSON.


## Funcionalidades

- Subir videos: Los usuarios pueden subir videos proporcionando información básica como el título, la URL del video y la imagen del perfil.

- Listado de Videos: Muestra una lista de todos los videos almacenados en la plataforma.

- Filtrado de Videos: Permite a los usuarios buscar viedeos utilizando palabras claves. 


## Screenshots
- Lista de videos
    ![image](https://github.com/DevDanielaCN/Alura-play/assets/157720284/e41d583e-f7e0-4d70-be44-1c79d183c207)

- Subir Video
    ![image](https://github.com/DevDanielaCN/Alura-play/assets/157720284/237aaaa5-370f-4b04-a52f-dca441ff4cfa)

- Filtrar
    ![image](https://github.com/DevDanielaCN/Alura-play/assets/157720284/d229f988-9b56-48cd-9c1e-33dc76f88591)

## Tecnologías Utilizadas

- Node.js
- JavaScript
- HTML/CSS


## Instalación

Clona el proyecto

```bash
  git clone https://github.com/DevDanielaCN/Alura-play.git
```

Ve al directorio del proyecto

```bash
  cd my-project
```

Instala las dependencias

```bash
  npm install
```


Inicia el Servidor JSON

```bash
  npx json-server --watch db.json --port 3001
```

Abre el archivo 'index.html' en tu navegador


## Curso

Este proyecto se basa en el curso [JavaScript: creando solicitudes](https://app.aluracursos.com/course/javascript-creando-solicitudes), impartido por Jose Viera en Alura Cursos. 
