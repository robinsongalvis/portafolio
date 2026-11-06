# Portafolio · Robinson Galvis

Sitio personal de una sola página: `index.html`. Sin dependencias ni proceso de build.

## Publicar en Vercel

1. Crear el repositorio `portafolio` en GitHub y subir esta carpeta.
2. En Vercel: **Add New → Project → Import** `portafolio` → Framework **Other** → **Deploy**.
3. En **Settings → Domains** cambiar a `robinsongalvis.vercel.app` (o un dominio propio).

Con Claude Code, desde esta carpeta:

```
Este es mi portafolio personal (index.html). Inicializa git, crea el repositorio público
"portafolio" en mi cuenta de GitHub con gh, haz el primer commit y súbelo. Después
despliégalo en Vercel con "vercel --prod" como proyecto estático y dame la URL final.
```

## Editar

- Textos: buscar la frase en `index.html` y cambiarla.
- Foto: reemplazar el `src` de `<img id="avatarImg">` por la foto (ideal cuadrada, ≥ 600 px).
- Contacto: buscar `davidgalvis1519@gmail.com` y `573203574674`.

Lea `CONTEXTO.md` antes de pedir cambios grandes: ahí están las reglas acordadas y los pendientes.
