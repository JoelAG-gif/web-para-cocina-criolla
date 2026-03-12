# 🍽️ Cocina Criolla — Sitio Web del Restaurante

Sitio web completo migrado a [Astro](https://astro.build/) con carrito de pedidos, panel de administración y envío por WhatsApp.

---

## 🚀 Cómo subir a GitHub y desplegar en Vercel

### Paso 1 — Instalar dependencias (solo la primera vez)

Necesitas tener [Node.js](https://nodejs.org/) instalado (versión 18 o superior).

```bash
npm install
```

### Paso 2 — Probar en local

```bash
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

---

### Paso 3 — Subir a GitHub

1. Ve a [github.com](https://github.com) y crea una cuenta si no tienes.
2. Haz clic en **"New repository"** → ponle el nombre `cocina-criolla` → **"Create repository"**.
3. En tu computadora, abre una terminal en la carpeta del proyecto y ejecuta:

```bash
git init
git add .
git commit -m "Primer commit - Cocina Criolla"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/cocina-criolla.git
git push -u origin main
```

> Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub.

---

### Paso 4 — Desplegar en Vercel

1. Ve a [vercel.com](https://vercel.com) y crea una cuenta (puedes usar tu cuenta de GitHub).
2. Haz clic en **"Add New Project"**.
3. Conecta tu repositorio `cocina-criolla` de GitHub.
4. Vercel detectará automáticamente que es un proyecto Astro.
5. Haz clic en **"Deploy"** → ¡listo!

Tu sitio estará en línea en una URL como `https://cocina-criolla.vercel.app`.

---

## 📁 Estructura del proyecto

```
cocina-criolla/
├── public/
│   └── images/          ← Imágenes del restaurante y platos
├── src/
│   ├── pages/
│   │   └── index.astro  ← Página principal
│   └── styles/
│       └── global.css   ← Todos los estilos
├── astro.config.mjs
├── package.json
└── README.md
```

## ✨ Funcionalidades

- 🧭 Navegación fija con scroll suave
- 🖼️ Hero con colage de imágenes
- 🍽️ Menú dinámico con categorías y filtros
- 🛒 Carrito de pedidos con envío por WhatsApp
- ⭐ Sección de reseñas
- 📅 Formulario de reservas vía WhatsApp
- 🔧 Panel de administración (contraseña: `admin123`)
- 💾 Datos guardados en localStorage del navegador
