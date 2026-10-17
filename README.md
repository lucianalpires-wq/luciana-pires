# Luciana Pires — Portfolio

Sitio estático (HTML + imágenes) publicado con GitHub Pages.

## Estructura
- `index.html` — página única del portfolio
- `luciana-pires.jpg` — retrato (también imagen para redes / og:image)
- `images/` — imágenes de los casos (FARM Rio × Barbour, Olympikus, Película)

## Publicar en GitHub Pages
1. Crear un repo nuevo en GitHub (p. ej. `luciana-pires-site`), vacío.
2. Desde esta carpeta:
   ```bash
   git remote add origin https://github.com/<usuario>/luciana-pires-site.git
   git push -u origin main
   ```
3. En el repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. En 1–2 minutos queda en `https://<usuario>.github.io/luciana-pires-site/`.

## Ver en local
Abrir `index.html` en el navegador, o:
```bash
python3 -m http.server 8000
```
