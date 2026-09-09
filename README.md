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
2. En `Settings > Pages`, en `Build and deployment > Source`, selecciona `GitHub Actions` y guarda.
3. Ve a `Actions` y espera a que termine `Deploy KINET to GitHub Pages`.
4. La URL pública será `https://<usuario>.github.io/<repositorio>/`.

La primera activación de Pages debe hacerse desde `Settings > Pages`. El `GITHUB_TOKEN` del workflow puede desplegar el sitio, pero no puede habilitar Pages por primera vez.
