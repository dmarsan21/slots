# 🎰 El Tío Kike - Cyber-Casino Landing Page

<div align="center">
  <img alt="Astro" src="https://img.shields.io/badge/Astro-0C1424?style=for-the-badge&logo=astro&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
</div>

<br />

Una landing page moderna y audaz para **El Tío Kike**, enfocada en promoción de casino en línea y bonos de afiliación. Diseñada con un vibrante estilo "Cyber-Casino", destacando tonos oscuros, luces de neón y atrevidos efectos *glassmorphism* para ofrecer una experiencia inmersiva orientada a generar la máxima conversión.

## ✨ Características Principales

*   **Diseño Cyber-Casino**: Interfaz visualmente impactante, temática nocturna.
*   **Optimización Mobile-First**: Configuración completamente responsiva (adaptable) que asegura la mejor experiencia en cualquier dispositivo.
*   **Sección de Big Hits**: Integración y display optimizado de miniaturas de videos destacados en YouTube.
*   **Grilla de Afiliados**: Cuadrícula de tarjetas dinámicas para las distintas promociones y bonos a reclamar.
*   **Efectos Premium**: *Glassmorphism*, transiciones suaves y estados interactivos en hover para todos los botones.
*   **Performance Absoluta**: Generada bajo Astro para tener tiempos de carga prácticamente nulos.

## 🛠️ Tecnologías

*   **Framework Fundamental**: [Astro](https://astro.build/)
*   **Framework de Estilización**: [Tailwind CSS v4](https://tailwindcss.com/)
*   **Funciones Adicionales**: TypeScript, integración de optimización de imágenes (Sharp).

## 🚀 Primeros Pasos

Sigue estas sugerencias para lanzar rápidamente el proyecto en tu entorno local:

1. **Clona este proyecto u obtén el código** y ubícate en el directorio matriz:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd casino
   ```

2. **Instala las dependencias necesarias** con tu manejador de paquetes preferido (está preparado con `pnpm`):
   ```bash
   pnpm install
   # o bien
   npm install
   ```

3. **Inicia el servidor de desarrollo:**
   ```bash
   pnpm run dev
   ```
   > Ahora puedes entrar y observar cambios en tiempo real en [http://localhost:4321](http://localhost:4321).

## 📦 Scripts Disponibles

Todos los comandos se corren en la terminal desde el root del proyecto:

| Comando | Acción |
| :--- | :--- |
| `npm run dev` | Inicia un servidor local de tests en `localhost:4321` |
| `npm run build` | Compila la versión de producción en el directorio `./dist/` |
| `npm run preview` | Previsualiza tu sitio buildeado antes de cargarlo al servidor |
| `pnpm astro ...` | Corre comandos del CLI propio de Astro |

## 📁 Estructura del Proyecto

A simple vista, en el explorador de archivos encontrarás un sistema prolijo como este:

```text
/
├── public/                 # Archivos estáticos como los favicon e imágenes raw
├── src/
│   ├── components/         # Todos los bloques dinámicos UI (Navbar, Hero, AffiliateGrid, BigHits, Footer)
│   ├── layouts/            # Archivos que le dan estructura al sitio completo o wrappers globales
│   ├── pages/              # Archivos de rutas base (.astro o .md) (index.astro)
│   └── styles/             # Entradas principales de CSS (global.css) configurando directivas Tailwind
├── astro.config.mjs        # Configuración modular de Astro
└── package.json            # Scripts de comando y dependencias instaladas
```

## 🌐 Próximos Pasos para Despliegue (Deploy)

Este proyecto está optimizado y preparado para un despliegue sin fallas. Se ajusta perfectamente al hosting en **GitHub Pages**, **Vercel** o **Netlify**.

Una vez subas tu código al repositorio de GitHub:
- Solo conecta tu cuenta en plataformas de hosting Vercel/Netlify usando el inicio un-click para Astro.

Si prefieres usar GitHub Pages, asegúrate de visitar la [Guía de Astro para GitHub Pages](https://docs.astro.build/es/guides/deploy/github/).

---

<p align="center">Construido con Astro 🚀 para el mejor rendimiento posible.</p>
