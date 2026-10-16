# Supervisión Escolar 072 — Prototipo estático corregido

Prototipo visual y navegable de cinco pantallas para la evidencia de residencia profesional (actividad 4: Diseño de interfaz y navegación).

## Pantallas

- P-01 Acceso de demostración
- P-02 Panel principal
- P-03 Avisos
- P-05 Solicitudes
- P-07 Entrega y revisión de evidencias

Todos los datos son ficticios. El prototipo no realiza autenticación, no transmite formularios ni carga archivos. El selector de perfil sirve solo para comparar vistas visuales; no implementa permisos reales.

## Abrir en tu equipo

Extrae todo el ZIP y abre `index.html` con Chrome, Edge o Firefox. No necesitas instalar Node.js, React, Vite ni Firebase. No debes abrir el ZIP sin extraerlo.

Los archivos `index.html`, `app.js` y `styles.css` deben quedar en la misma carpeta.

## Subir a GitHub

1. Crea un repositorio en GitHub, por ejemplo `supervision-escolar-072`.
2. Extrae el ZIP.
3. Sube los archivos **que están dentro** de la carpeta extraída a la raíz de tu repositorio: `index.html`, `app.js`, `styles.css`, `netlify.toml`, `README.md`.
4. Comprueba que `index.html` se encuentre directamente en la raíz, no dentro de una subcarpeta adicional.

## Desplegar en Netlify

**Desde GitHub:** Netlify → Add new project → Import an existing project → GitHub → selecciona el repositorio. En la configuración de compilación, deja el comando de build vacío y directorio de publicación `.` (punto). `netlify.toml` ya indica la carpeta de publicación.

**Manualmente:** En Netlify puedes usar el despliegue manual arrastrando la carpeta extraída que contiene `index.html` (no arrastres solo `app.js` ni la carpeta externa que no contenga el index).

Esta versión no tiene `npm install`, no requiere `npm run build`, y no requiere una carpeta `dist`.

## Comprobaciones rápidas

- Debe aparecer la portada de acceso inmediatamente.
- Al presionar **Entrar a la demostración**, abre **Panel principal**.
- Menú lateral: **Avisos**, **Solicitudes** y **Evidencias**.
- En **Solicitudes**, prueba los filtros de estado.
- Cambia el perfil usando el selector superior.
- Prueba las pantallas desde un teléfono (diseño adaptable).

## Documentación de residencia

Guarda capturas de la portada, panel, avisos, solicitudes y evidencias, junto con la URL pública de Netlify y el enlace del repositorio en GitHub. Identifica el producto como *prototipo estático*, no como sistema funcional.
