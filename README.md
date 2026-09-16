# RTech Soluciones Informática — Landing Page

Sitio web estático (HTML, CSS y JS en un solo archivo, sin frameworks ni build) para el taller de armado y reparación de PC **RTech Soluciones Informática**, San Miguel de Tucumán.

## Archivos

- `index.html` — Landing principal one-page: Inicio, Servicios, Antes y Después, Nosotros, Preguntas frecuentes y Contacto (formulario + mapa + horarios). Las fotos del taller y el logo van incrustados directamente en el archivo (en base64), así que no depende de una carpeta `assets/` aparte ni se puede romper al subir el repo a GitHub.
- `diagnostico-sin-cargo.html` — Sub-página de campaña (embudo largo): hero, prueba social, beneficios, características, cómo funciona, testimonios, oferta, garantía, FAQ y cierre. Pensada para compartir en anuncios o WhatsApp.

Ambas páginas comparten paleta de marca (fondo `#121212`, cyan `#00D2FF`, verde WhatsApp `#25D366`), tipografías Poppins/Inter, y un botón flotante de WhatsApp.

## Publicar con GitHub Pages

1. Subí este repo a GitHub (ver pasos abajo).
2. En el repo: **Settings → Pages → Source: rama `main`, carpeta `/ (root)`**.
3. En unos minutos el sitio queda publicado en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Pendiente de completar

- Reemplazar los testimonios de ejemplo por reseñas reales de clientes.
- Si tenés el pin exacto de Google Maps del local, actualizar el `src` del `iframe` del mapa en `index.html`.
- Las etiquetas `og:image` y el `image` del schema.org (para vistas previas al compartir el link) siguen apuntando a `assets/despues-limpieza.jpg`, que no existe como archivo separado — si querés que la vista previa de WhatsApp/Facebook muestre una foto, hay que subir esa imagen a un hosting público y actualizar esa URL.

## Licencia

© RTech Soluciones Informática.
