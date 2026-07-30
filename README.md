# Kailand Web

Sitio web oficial de Kailand, construido con [Astro](https://astro.build) + React + Tailwind CSS v4.

## Tecnologías

- **Astro v7** — Framework web
- **React** — Componentes interactivos
- **Tailwind CSS v4** — Estilos utilitarios vía `@tailwindcss/vite`
- **TypeScript** — Tipado estático
- **AOS** — Animaciones al hacer scroll

## Estructura

```
.
├── public/                  # Archivos estáticos
├── src/
│   ├── assets/img/          # Imágenes y recursos
│   ├── components/          # Componentes (Astro y React)
│   │   ├── react/           # Componentes React
│   │   └── ...
│   ├── icons/               # Iconos SVG
│   ├── js/                  # Scripts JS
│   ├── layouts/             # Layouts
│   ├── pages/               # Páginas (rutas)
│   └── styles/              # Estilos globales
├── archive/                 # Páginas antiguas archivadas
├── astro.config.mjs
├── global.css               # Entry point de Tailwind
└── tsconfig.json
```

## Comandos

| Comando               | Acción                                |
| :-------------------- | :------------------------------------ |
| `npm install`         | Instalar dependencias                 |
| `npm run dev`         | Servidor local en `localhost:4321`    |
| `npm run build`       | Build producción en `./dist/`          |
| `npm run preview`     | Vista previa del build local          |
| `npm run astro check` | Chequeo de tipos y errores            |

## Despliegue

Se despliega automáticamente en GitHub Pages mediante GitHub Actions al hacer push a `main`.

## Licencia

MIT &copy; 2024 GatoArtStudio
