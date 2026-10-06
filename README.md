# Landing Voy a Enviarlo

Landing page estática lista para publicar en Vercel.

## Antes de publicar

En `index.html` cambia:

- `56900000000` por el número real de WhatsApp.
- El enlace `href="#"` de Instagram por la URL real de la cuenta.

## Publicar en Vercel

### Opción 1: GitHub
1. Sube esta carpeta a un repositorio de GitHub.
2. Entra a Vercel.
3. Selecciona **Add New > Project**.
4. Importa el repositorio.
5. Presiona **Deploy**.

### Opción 2: Vercel CLI
```bash
npm install -g vercel
cd voya-enviarlo-landing
vercel --prod
```

No requiere build ni dependencias.
