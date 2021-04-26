# Evaluación final María Núñez. Módulo HTML y CSS

Esta es mi evaluación final del **Módulo 1** de Adalab, realizada con lo aprendido durante las primeras 3 semanas del bootcamp. Para este proyecto he contado con el **Adalab Web Starter Kit** creado en **node y gulp**, una **plantilla de proyecto con funcionalidades preinstaladas y preconfiguradas**.

## Requerimientos

- Usar Sass.
- Usar flexbox y CSS Grid.
- Usar media queries.
- Resolver algunas interacciones usando transiciones y animaciones.

## Sobre Adalab Web Starter Kit

En el Kit hay 3 tipos de ficheros y carpetas:

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, CSS, JS...
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

### Estructura de carpetas

La estructura de carpetas tiene esta pinta:

```
src
 ├─ api // los ficheros de esta carpeta se copian en public/api/
 |  └─ data.json
 ├─ images
 |  └─ logo.jpg
 ├─ js // los ficheros de esta carpeta se concatenan en el fichero main.js y este se guarda en public/main.js
 |  ├─ main.js
 |  └─ events.js
 ├─ scss
 |  ├─ components
 |  ├─ core
 |  ├─ layout
 |  └─ pages
 └─ html
    └─ partials
```

### Más información sobre el Starter Kit utilizado

> Para más información sobre [Adalab Web Starter Kit](https://github.com/Adalab/adalab-web-starter-kit) recomiendo visitar su repositorio.

## Si quieres clonar este repositorio necesitarás seguir estos pasos para trabajar con el Starter Kit:

1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```

2. Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que te pongas a programar.** Para ello ejecuta el comando:

```bash
npm start
```

Este comando:

- **Abre una ventana del navegador y muestra tu página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **se actualice en tu navegador**.
- También **procesa los ficheros** HTML, SASS / CSS y JS y los **genera y guarda en la carpeta `public/`**. Por ejemplo:
  - Convierte los ficheros SASS en CSS.
  - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

3. Después de ejecutar `npm start` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/` y programar cómodamente.

4. Si quieres utilizar Github Pages para generar tu página para producción, ejecuta el comando:

```bash
npm run docs
```

Y a continuación:

1. Sube a tu repo la carpeta `docs/` que se te acaba de generar.
1. Entra en la pestaña `settings` de tu repo.
1. Y en el apartado de GitHub Pages activa la opción **master branch /docs folder**.
