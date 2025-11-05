# 🏆 Proyecto Bundesliga – API REST + Interfaz Web

## 📖 Descripción del proyecto

Este proyecto consiste en el desarrollo de una **aplicación web completa** inspirada en la **Bundesliga**, la liga alemana de fútbol profesional.  
El sistema permite **gestionar información relacionada con los equipos, entrenadores, estadios y equipaciones**, ofreciendo tanto una **API REST** funcional como una **interfaz web interactiva** para el usuario.

El trabajo se ha desarrollado como parte de los módulos de:
- **Bases de Datos**
- **Desarrollo Web en Entorno Servidor**
- **Desarrollo Web en Entorno Cliente**

del ciclo formativo de **1º de DAW (Desarrollo de Aplicaciones Web)**.

---

## ⚙️ Tecnologías utilizadas

### 🧩 Backend
- **Node.js** – Entorno de ejecución de JavaScript en servidor.  
- **Express.js** – Framework para crear la API y gestionar rutas.  
- **MongoDB** – Base de datos NoSQL utilizada para almacenar los datos.  
- **Monk** – Librería ligera para conectar y realizar operaciones sobre MongoDB.

### 🎨 Frontend
- **HTML5 + CSS3 + JavaScript**  
- **JSRender** – Motor de plantillas utilizado para renderizar dinámicamente los datos en el navegador.  
- **Picnic CSS** – Framework CSS minimalista para el diseño visual.  

### 🧪 Herramientas adicionales
- **Postman / Thunder Client** – Para probar las rutas de la API.  
- **Nodemon** – Para reiniciar automáticamente el servidor durante el desarrollo.  
- **Git / GitHub** – Control de versiones y repositorio del proyecto.

---

## 🧠 Objetivos del proyecto

- Diseñar y desarrollar una **API RESTful** funcional.  
- Implementar operaciones **CRUD (Crear, Leer, Actualizar, Eliminar)** en todas las entidades.  
- Conectar el backend con **MongoDB** mediante Monk.  
- Crear una **interfaz web interactiva** que consuma la API.  
- Aplicar buenas prácticas de estructura, modularización y documentación.

---

## 🧩 Estructura del proyecto
## 🧩 Estructura del proyecto

```plaintext
📁 bundesliga/
├── 📂 db/                 # Conexión con la base de datos (MongoDB)
├── 📂 routes/             # Rutas y controladores de la API REST
│   ├── entrenadores.js
│   ├── equipos.js
│   ├── estadios.js
│   └── equipaciones.js
├── 📂 public/             # Archivos estáticos (HTML, CSS, JSRender, imágenes)
│   ├── index.html
│   ├── js/
│   │   ├── main.js
│   │   └── templates.js
│   └── css/
│       └── style.css
├── 📂 views/              # Plantillas JSRender (si están separadas)
├── 📜 server.js           # Servidor principal con configuración de Express
├── 📜 package.json        # Dependencias y scripts
└── 📜 README.md           # Documentación del proyecto

