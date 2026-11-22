# template-verifica

Template pronto all'uso e **100% offline** per verifiche con **Bootstrap 4.6.2**, **jQuery 3.7.1** e **IntelliSense locale** in VS Code (senza bisogno di internet né di `node_modules`).

## Struttura

- `index.html` — pagina HTML5 già collegata a Bootstrap, jQuery, `css/style.css` e `js/script.js`
- `css/bootstrap.min.css` (+ `.map`) — Bootstrap 4.6.2
- `js/jquery.min.js` (+ `.map`) — jQuery 3.7.1 (versione completa, include `$.ajax` e animazioni)
- `js/bootstrap.bundle.min.js` (+ `.map`) — Bootstrap 4.6.2 con Popper.js incluso
- `js/script.js` — script personalizzato con `$(function () { ... })`
- `types/` + `jsconfig.json` — definizioni TypeScript locali (`jquery`, `sizzle`, `bootstrap`, `popper.js`) per avere IntelliSense completo anche completamente offline
