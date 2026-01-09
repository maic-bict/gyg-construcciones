# G y G Construcciones

Sitio web estático de G y G Construcciones y Remodelaciones.

Descripción: Sitio para presentar servicios, cotización preliminar y contacto.

Instrucciones de uso:
1. Coloca `index.html` en la raíz del repositorio.
2. Para GitHub Pages: activa Pages en Settings → Pages, rama `main`, carpeta `/ (root)`.
3. Si subes a un host, asegúrate de que `index.html` esté en la carpeta pública (public_html o similar).

Contacto:
- WhatsApp: +57 320 896 7267
- Email: garciamaicolrojas28@gmail.com
``` ````

Instrucciones breves para crear el .zip y subir (elige según tu sistema)

- Windows (PowerShell)
  1. Guarda los dos archivos en una carpeta llamada gyg-website.
  2. Abre PowerShell en la carpeta padre y ejecuta:
     Compress-Archive -Path .\gyg-website\* -DestinationPath .\gyg-website.zip -Force

- macOS / Linux (terminal)
  1. Crea carpeta y guarda archivos: mkdir gyg-website && mv index.html README.md gyg-website/
  2. Comprimir:
     cd gyg-website/..
     zip -r gyg-website.zip gyg-website

- Alternativa rápida (Windows): crea la carpeta, pega los archivos, clic derecho → Enviar a → Carpeta comprimida (zip).

Después de crear el .zip:
- Puedes subirlo a GitHub desde la web (al crear repo) o clonar el repo y empujar los archivos:
  git init
  git add index.html README.md
  git commit -m "Add website index.html"
  git branch -M main
  git remote add origin git@github.com:maic-bict/gyg-construcciones.git
  git push -u origin main

¿Quieres que te genere también un archivo .gitignore (ej. para ignorar .DS_Store) o un pequeño archivo LICENSE (MIT) para añadir al repo?