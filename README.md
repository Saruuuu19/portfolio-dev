# 🚀 Portafolio Web — Andrés Retamoso

Portafolio web personal para presentar proyectos, trayectoria y formas de contacto. Desarrollado con **Astro 5**, **Tailwind CSS v4** y tipografías **Geist**.

---

## 🛠️ Tecnologías y Herramientas

- **Framework:** [Astro 5](https://astro.build/)
- **Estilos:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Tipografías:** [Geist Font Family](https://vercel.com/font) (Geist, Geist Mono & Geist Pixel)
- **Empaquetador & Dev Server:** Vite
- **Gestor de Paquetes:** `pnpm`

---

## 📂 Estructura del Proyecto

```text
portfolio-dev/
├── agents/              # Instrucciones y documentación de agentes
├── public/              # Recursos estáticos y archivos de fuentes (.woff2)
│   ├── favicon.svg
│   └── fonts/           # Fuentes Geist, Geist Mono y Geist Pixel
├── src/
│   ├── components/      # Componentes de la interfaz (Header, etc.)
│   ├── layouts/         # Layouts de las páginas (Layout.astro)
│   ├── pages/           # Rutas y páginas del sitio (index.astro, etc.)
│   └── styles/          # Estilos globales y variables de Tailwind (global.css)
├── astro.config.mjs     # Configuración de Astro e integración con Tailwind
└── package.json
```

---

## ⚙️ Comandos del Proyecto

| Comando        | Descripción                                                       |
| :------------- | :---------------------------------------------------------------- |
| `pnpm install` | Instala las dependencias del proyecto                             |
| `pnpm dev`     | Inicia el servidor de desarrollo local en `http://localhost:4321` |
| `pnpm build`   | Compila el sitio estático optimizado para producción en `/dist`   |
| `pnpm preview` | Previsualiza localmente el resultado de la compilación            |
