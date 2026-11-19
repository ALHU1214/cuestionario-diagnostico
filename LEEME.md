# Cuestionario de diagnóstico · AI MANGANELL

Para publicar en https://diagnostico.aimanganell.com (GitHub Pages, repo ALHU1214/cuestionario-diagnostico).

- `index.html` es una copia de `Personales/kits/kit-diagnostico-procesos/formulario/formulario.html`.
  Si se cambia el cuestionario en el kit (`/personalizar-cuestionario`), se vuelve a copiar aquí y se sube.
- El cliente lo rellena, pulsa «Descargar mis respuestas» y manda el `.json`. Nada se envía a ningún servidor.
- `robots.txt` lo deja fuera de Google: es para mandar el enlace a clientes, no para que lo encuentren.
- DNS: `diagnostico` CNAME → `alhu1214.github.io`, en Cloudflare en «solo DNS» (nube gris).
