# web3

Portafolio web estático con ejemplos y demos 3D implementados con A-Frame y MindAR. El proyecto es 100% HTML y contiene una página principal (index.html) que enlaza con 5 ejercicios interactivos (ex1..ex5) y recursos multimedia en la carpeta `imatges`.

Vista previa
------------

- Repositorio: https://github.com/Pistacho666/web3
- Abre `index.html` en tu navegador o despliega con GitHub Pages para ver la versión pública.

## Estructura del repositorio

- index.html — Página principal (idioma: catalán)
- ex1/ — Ejemplo 1 (ex1.html)
- ex2/ — Ejemplo 2 (ex2.html)
- ex3/ — Ejemplo 3 (ex3.html)
- ex4/ — Ejemplo 4 (ex4.html)
- ex5/ — Ejemplo 5 (ex5.html)
- imatges/ — Imágenes y favicon
- .github/ — (configuración de GitHub si existe)

## Contenido destacado (relacionado con los ejercicios)

- EX1 – Introducción A-Frame: `ex1/ex1.html`
- EX2 – Model 3D (GLB): `ex2/ex2.html`
- EX3 – Realidad Aumentada con MindAR: `ex3/ex3.html`
- EX4 – Saturn abstracto con A-Frame: `ex4/ex4.html`
- EX5 – "Passadís del terror" (escena VR): `ex5/ex5.html`

## Cómo usar (local)

1. Clona el repositorio:
   ```
   git clone https://github.com/Pistacho666/web3.git
   cd web3
   ```
2. Abrir en el navegador:
   - Doble clic en `index.html`, o
   - Servidor local (recomendado para evitar problemas con fetch/CORS):
     - Python 3:
       ```
       python -m http.server 8000
       ```
       y abre http://localhost:8000
     - Node.js (serve):
       ```
       npm install -g serve
       serve .
       ```

## Despliegue (GitHub Pages)

1. En el repositorio de GitHub: Settings → Pages.
2. Selecciona la rama (p. ej. `main`) y la carpeta raíz (`/`).
3. Guarda y espera unos minutos. URL: `https://Pistacho666.github.io/web3` (si GitHub Pages está habilitado).

## Buenas prácticas y advertencias

- Mantén contenido estático (HTML/CSS/JS) separado en carpetas (`css/`, `js/`) si amplías el proyecto.
- Si integras funcionalidades blockchain o debes usar claves, NUNCA pongas claves privadas en el frontend.
- Usa `loading="lazy"` en imágenes grandes (ya está aplicado en el sitio) para mejorar el rendimiento.
- Comprueba la compatibilidad móvil (ya hay media queries básicas en `index.html`).

## Cómo contribuir

- Fork → crear rama descriptiva → PR con cambios.
- Para correcciones de contenido: crear rama `fix/<tema>` o `docs/<mejora>`.
- Si añades dependencias o build tools, incluye instrucciones claras en el README y añade `.gitignore` adecuado.

## Sugerencias de mejoras

- Separar CSS y JS en archivos propios y minimizarlos para producción.
- Añadir un archivo `LICENSE` (ej. MIT) si quieres permitir reutilización.
- Añadir un `README.md` en catalán/inglés si quieres público internacional.
- Añadir miniaturas optimizadas en `imatges/` y WebP para mejorar carga.
- Incluir badges (GitHub Pages, licencia, estado) en la cabecera del README.

## Licencia

No hay licencia en el repositorio actualmente (según el contenido revisado). Si quieres, puedo añadir un `LICENSE` (por ejemplo MIT). Indica qué licencia prefieres y la genero.

## Autor / Créditos

- Autor (según `index.html`): Andrés Daniel Torres Pérez
- Contacto GitHub: https://github.com/Pistacho666

## Notas finales

He añadido el snippet solicitado al README.md y he subido el archivo al repositorio. Si quieres que haga cambios (traducción, añadir capturas, badges, o crear el archivo LICENSE), dime qué prefieres y lo actualizo.