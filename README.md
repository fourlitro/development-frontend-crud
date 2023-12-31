# development-frontend-crud
# Beta Residencial - Sistema de Ventas

Beta Residential sales system repository for ISI developments.

This page is a fictitious project developed in HTML, SASS and Javascript as part of the Frontend Development class.

The “Residential Beta - Sales System” project is a web application designed to exemplify web development focused on JavaScript to the students of the Frontend Design class. This application allows you to consult the house models of a fictitious residential area,
make sales of these house models and view sales indicators or reports.

This project is in development, so the documentation presented may describe incomplete functionality or in the process of development.

## System Requirements

Before starting,
Make sure you have the following requirements installed on your system:

- **Node.js**: Version 12 or higher. You can download it from [nodejs.org](https://nodejs.org/).
- **npm**: Version 6 or higher. npm is usually installed along with Node.js.


## Project installation
Once you have Node.js and npm installed,
Follow these steps to install and configure the project in your local development environment:

1. Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/fourlitro/development-frontend-crud.git
```

2. Navigate to the project directory:

```bash
cd development-frontend-crud
```

3.
Install the project dependencies using npm (Node Package Manager):

```bash
npm install
```

4. Start the development server. This will automatically open the application in your default web browser:

```bash
npm start
```

5. Sass styles will be compiled automatically as you work on the project.
No additional action is required.

## Technologies Used

- HTML: For the structure of web pages.
- Sass: A CSS preprocessor for more efficient styling.
- JavaScript: For logic and user interaction.

## Project structure

Initial project structure based on components:

```bash

Ventas/                   # Carpeta principal del proyecto
│
├── src
│   ├── assets/           # Carpeta que almacena archivos estáticos
│   │    ├── scss/        # Carpeta para archivos de SASS
│   │    ├── css/         # Carpeta para archivos CSS compilados
│   │    └── img/         # Carpeta para images estaticas
│   │
│   │
│   ├── real-estate/      # Carpeta para el catalogo de modelos
│   │    ├── index.html   # Página HTML de modelos
│   │    └── script.js    # JavaScript específico de modelos
│   │
│   │
│   ├── sales/            # Carpeta de modulo de ventas
│   │    ├── index.html   # Página HTML de ventas
│   │    └── script.js    # JavaScript específico de ventas
│   │
│   │
│   ├── shared/           # Carpeta con recursos compartidos y de uso generico
│   │    └── utils.js     # JavaScript con funciones y utilidades genericas
│   │
│   │
│   └─── index.html       # Archivo HTML principal con home
│
│
├── README.md             # Documentación del proyecto
│
├── package.json

```