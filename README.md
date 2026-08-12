# La Pizzata — Carta pública

Página del menú de La Pizzata (Calama), pensada como destino del QR de la
paloma del local. Publicada con GitHub Pages para que funcione como link
plano en cualquier navegador, sin depender de apps ni login.

Se genera desde `scripts/generar_carta.py` en el repo principal
(privado) de contenido/redes sociales — los datos (precios, ingredientes)
son la misma fuente de verdad. Para actualizarla: reexportar `index.html`
desde ese script y subir el archivo acá.

100% HTML/CSS estático, sin dependencias externas (tipografías y logo
embebidos en base64) — no se rompe si cambia algo fuera de este repo.
