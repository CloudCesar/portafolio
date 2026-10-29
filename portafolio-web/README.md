# Portafolio de César Osorio

Sitio estático de una sola página. No necesita instalar nada ni compilar.

## Archivos
- `index.html`: la página completa (estilos y código incluidos).
- `favicon.svg`: ícono de la pestaña.
- `vercel.json`: configuración de Vercel.

## Verlo en tu computador
Abre `index.html` con doble clic.

## Subirlo a GitHub
1. En github.com, crea un repositorio nuevo (por ejemplo `portafolio`), sin README.
2. Pulsa **uploading an existing file** y arrastra todo el contenido de esta carpeta.
3. Pulsa **Commit changes**.

O desde la terminal, dentro de esta carpeta:

```bash
git init
git add .
git commit -m "Portafolio"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/portafolio.git
git push -u origin main
```

## Publicarlo en Vercel
1. Entra a vercel.com con tu cuenta de GitHub.
2. **Add New → Project** y elige el repositorio.
3. Framework Preset: **Other**. No cambies nada más.
4. Pulsa **Deploy**. Queda en `https://portafolio-xxxx.vercel.app`.

Cada cambio que subas a GitHub se publica solo.

## Actualizar
Edita `index.html` y súbelo de nuevo al repositorio.
