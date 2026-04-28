# Kaizen Task Logger

Web app ligera para registrar tareas en planta, medir tiempos y exportar un Excel para análisis SMED.

## Qué incluye
- Temporizador general
- Gestión de personas
- Tareas tipificadas sugeridas
- Marcado VA / MUDA
- Exportación a Excel
- Opción de guardar el Excel directamente en una carpeta local usando File System Access API (Chrome/Edge)

## Estructura del repo
- `index.html`: aplicación completa en un solo archivo

## Cómo usar en local
1. Descarga o clona el repositorio.
2. Abre `index.html` en **Chrome** o **Edge**.
3. Pulsa `📁 Carpeta` para elegir la carpeta de guardado si quieres guardar directamente allí.
4. Usa la app y al final pulsa `■ STOP / DESCARGAR`.

## Cómo subir a GitHub
### Opción A: repositorio nuevo desde la web
1. Crea un repositorio nuevo en GitHub.
2. Sube el archivo `index.html`.
3. Haz commit.

### Opción B: con Git en local
```bash
cd ruta/de/la/carpeta
 git init
 git add .
 git commit -m "Initial commit - Kaizen Task Logger"
 git branch -M main
 git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
 git push -u origin main
```

## Publicarlo con GitHub Pages
1. Entra en **Settings > Pages**.
2. En **Source**, elige `Deploy from a branch`.
3. Selecciona `main` y carpeta `/root`.
4. Guarda.
5. GitHub te dará una URL pública.

## Nota sobre la carpeta local
La opción `📁 Carpeta` funciona en navegadores compatibles con File System Access API.
- Funciona bien en **Chrome** y **Edge**.
- En navegadores no compatibles se usará la descarga normal.

## Nota sobre favicon
La app usa `KTL_LOGO.png` como favicon local. Si no lo subes al repo, la app seguirá funcionando, pero el icono de la pestaña no saldrá.
