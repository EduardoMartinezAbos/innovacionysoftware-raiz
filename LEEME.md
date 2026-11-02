# Redirección de innovacionysoftware.com

El DNS del .com está en Microsoft 365, que no deja apuntar la raíz del dominio a Cloudflare Pages.
Por eso la raíz (registro A de `@`) apunta a GitHub Pages, y esta página manda a cada visitante a
https://www.innovacionysoftware.com, conservando la ruta. La web de verdad está en el repositorio `tis-web`.

Si el dominio se transfiere a Cloudflare, este repositorio deja de hacer falta.
