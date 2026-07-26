# ViñaGuard Landing Page

![Astro](https://img.shields.io/badge/Astro-6.x-ff5d01?logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-06b6d4?logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-3D-black?logo=threedotjs&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Landing%20Page-success)

Landing page oficial de **ViñaGuard Tarija**, un proyecto de monitoreo inteligente para viñedos usando **drones + IA** para detección temprana de enfermedades, mapas de calor y decisiones de manejo más precisas.

## ✨ ¿Qué tiene de piola?

- Diseño moderno, seccionado y orientado a conversión.
- CTA directos por **WhatsApp** y formulario de contacto.
- Comparador visual: viñedo normal vs mapa de calor.
- Simulador interactivo de detección con IA (mildiu, oídio, botrytis, estrés hídrico).
- Calculadora de presupuesto por hectáreas.
- Mapa 3D interactivo de cobertura por municipios de Tarija.
- Secciones comerciales completas: problema, solución, beneficios, planes, cobertura, testimonios y equipo.

## 🧱 Stack técnico

- [Astro](https://astro.build/) (sitio estático + componentes `.astro`)
- [Tailwind CSS](https://tailwindcss.com/) (estilos utilitarios)
- [Three.js](https://threejs.org/) (render 3D del mapa de cobertura)

## 🚀 Instalación y ejecución

Requisitos:

- Node.js `>=22.12.0`
- pnpm

Instalar dependencias:

```bash
pnpm install
```

Levantar entorno local:

```bash
pnpm dev
```

Build de producción:

```bash
pnpm build
```

Previsualizar build:

```bash
pnpm preview
```

## 📜 Scripts disponibles

| Script | Descripción |
|---|---|
| `pnpm dev` | Inicia servidor de desarrollo |
| `pnpm build` | Genera build de producción en `dist/` |
| `pnpm preview` | Previsualiza el build |
| `pnpm astro` | Ejecuta comandos de Astro CLI |

## 🗂️ Estructura del proyecto

```text
/
├── public/
│   └── images/                 # Imágenes y assets estáticos
├── src/
│   ├── components/
│   │   ├── TarijaMap3D.astro   # Mapa 3D interactivo (Three.js)
│   │   └── sections/           # Secciones de la landing
│   ├── data/
│   │   └── tarijaMunicipios.json
│   └── pages/
│       └── index.astro         # Página principal única
├── astro.config.mjs
└── package.json
```

## 🎯 Propósito del repositorio

Este repo está enfocado en **marketing y captación de clientes potenciales** para ViñaGuard: mostrar claramente el valor del servicio y facilitar solicitudes de demostración/cotización.
