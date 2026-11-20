# Organizador de tareas · HC Liceo

Web para organizar cada partido en casa: partidos, departamentos y tareas por persona,
con un filtro por persona dentro de cada partido, tareas fijas y balance del partido.

- `public/index.html`: la web (HTML, CSS y JS a mano, sin dependencias).
- `netlify/functions/api.mts`: guarda los datos en Netlify Blobs (`/api/datos`, `/api/escribir`).
- **Los datos no están en el repositorio**: viven en Netlify.
- Acceso con dos claves (variables de entorno en Netlify): `CLAVE_EQUIPO` (ver) y `CLAVE_EDICION` (ver y cambiar).
  Enlace directo: `https://<web>/?k=<clave>`.
