# KOS site preview

Preview estático del sitio de KOS, publicado con GitHub Pages para revisión
interna. El código fuente vive en el repo privado `jesusmlpd/social`.

Este export es solo para revisar diseño y contenido. Dos cosas no funcionan aquí
porque un sitio estático no tiene servidor:

- El formulario de contacto no envía. En producción usa `/api/contact` con Resend.
- La redirección automática de idioma la hace un `index.html` en lugar del
  middleware de Next.

Para regenerarlo, desde el repo privado:

```bash
bash scripts/build-pages.sh /kos-site
```
