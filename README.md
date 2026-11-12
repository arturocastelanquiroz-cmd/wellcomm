# WellCOMM · App del residente (piloto)

Prototipo navegable de la app del residente en la etapa piloto, pensado para abrirse en el navegador del celular. Datos y personas ficticios.

Diseño de producto: RANDOM INTERACTIVE · noviembre 2026.

## Pantallas

Bienvenida · Inicio · Avisos · Reportar algo · Seguimiento y calificación · Mis reportes · Botón de pánico · Visitas (pase QR, visita no anunciada) · Paquetería · Perfil · Qué comparto con mis papás · Derechos ARCO.

Enlaces directos: `/#inicio`, `/#sos`, `/#reportar`, `/#visitas`, `/#paquetes`, `/#perfil`.
La primera vez abre en la bienvenida; después abre directo en Inicio ("Cerrar sesión" en Perfil la vuelve a mostrar).

## Publicar en Vercel

1. Sube estos archivos a la raíz de un repositorio de GitHub.
2. Vercel → Add New → Project → Import el repositorio.
3. Framework preset: **Other**, sin build command, output directory `.`.
4. Deploy. Cada `git push` a `main` vuelve a publicar.

## En el celular

Abre la URL de Vercel y usa **Compartir → Agregar a inicio** (iPhone) o **⋮ → Agregar a pantalla principal** (Android). Se abre a pantalla completa, con ícono propio y sin barra del navegador.
