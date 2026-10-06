# MS Capital · mscapsol.com

Sitio de MS Capital. La portada presenta a la firma; el equipo destaca a Tere Silva como asesora principal, seguida de Alfredo Moya Silva y Alfredo Moya Santos.

## Cómo editar desde GitHub

1. Abre el archivo que quieras cambiar.
2. Pulsa el icono del lápiz (Edit this file).
3. Modifica el contenido y pulsa **Commit changes**.
4. Guarda el cambio en la rama **main**. Cloudflare Pages publicará automáticamente la nueva versión.

| Archivo | Qué puedes cambiar |
| --- | --- |
| `index.html` | Textos, nombres, teléfonos, enlaces y contenido de las secciones. |
| `style.css` | Colores, tamaños, espacios y diseño. |
| `script.js` | Menú móvil y comportamiento de la página. |
| `assets/` | Fotografías y marca gráfica. |
| `robots.txt` y `sitemap.xml` | Información de indexación y dominio. |
| `_headers` | Cabeceras HTTP servidas por Cloudflare Pages. |

Para cambiar un texto, sustituye sus palabras conservando las etiquetas HTML. Por ejemplo, busca `Protegemos lo que hoy importa.` en `index.html`.

Para cambiar una foto sin editar el HTML, reemplaza el archivo de `assets/` por uno con el mismo nombre. Los perfiles de Tere Silva y Alfredo Moya Santos usan imágenes JPG y WEBP; actualiza ambas versiones cuando cambies sus fotos.

## Publicación

- Dominio principal: https://mscapsol.com/
- También disponible: https://www.mscapsol.com/
- Cloudflare Pages: proyecto `mscapsol-github`.
- Rama de producción: `main`.
- Sitio HTML estático, sin dependencias ni instalación.
- Framework: None.
- Comando de compilación: vacío.
- Directorio de salida: `/` (raíz del repositorio).

Los cambios en otras ramas generan vistas previas. Los cambios guardados en `main` actualizan el sitio público. Puedes consultar el estado en Cloudflare > Workers & Pages > mscapsol-github > Deployments.

## Vista previa local

Dentro de esta carpeta, ejecuta:

```bash
python -m http.server 8000
```

Después abre http://localhost:8000/.

El sitio teresilva.com y su repositorio Pagina-web-Tere son independientes.
