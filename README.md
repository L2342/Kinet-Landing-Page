# KINET

Landing page de KINET, un proyecto de Ingeniería Aplicada desarrollado por Iris Systems.

## Estructura

- `index.html`: sitio estático completo.
- `assets/images/`: logotipos, fotografías e imágenes del proyecto.
- `assets/models/`: modelo 3D utilizado por Three.js.

## Ejecutar localmente

Abre la carpeta con VS Code y usa Live Server, o ejecuta un servidor estático desde la raíz:

```bash
npx serve .
```

No abras `index.html` con doble clic: el modelo `.glb` necesita cargarse mediante `http://`.

## Publicar en GitHub Pages

1. Sube este contenido a un repositorio de GitHub.
2. En `Settings > Pages`, selecciona `Deploy from a branch`.
3. Selecciona la rama principal y la carpeta `/ (root)`.
4. Guarda y espera a que GitHub genere la URL pública.
