<div align="center">
  <h1 align="center">🎰 El Tío Kike - Cyber-Casino Landing Page</h1>
  <p align="center">
    <strong>Una landing page moderna y dinámica construida con Astro y Tailwind CSS, diseñada para la máxima conversión.</strong>
  </p>
  <p align="center">
    <a href="https://astro.build"><img src="https://img.shields.io/badge/Astro-0C1424?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" /></a>
    <a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" /></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  </p>
</div>

<br />

Una landing page moderna y audaz para **El Tío Kike**, enfocada en la promoción de casino en línea y bonos de afiliación. Diseñada con un vibrante estilo "Cyber-Casino", destacando tonos oscuros, luces de neón y atrevidos efectos *glassmorphism* para ofrecer una experiencia inmersiva orientada a generar la máxima conversión a través de interfaces amigables.

## ✨ Características Principales

- 🎨 **Diseño Cyber-Casino**: Interfaz visualmente impactante inspirada en la temática nocturna y de neón.
- 📱 **Mobile-First & Responsivo**: Configuración completamente adaptable que asegura la mejor experiencia en cualquier dispositivo, desde móviles hasta pantallas de alta resolución.
- 📺 **Sección de Big Hits**: Integración optimizada de miniaturas de videos destacados en YouTube.
- 🎁 **Grilla de Afiliados**: Cuadrícula de tarjetas dinámicas (Banners) para mostrar distintas promociones y bonos listos para reclamar.
- 💎 **Efectos Premium UI**: Implementación de *Glassmorphism*, transiciones fluidas y estados interactivos al pasar el cursor (hoverings) para todos los elementos clickeables.
- ⚡ **Performance Absoluta**: Construida con Astro para lograr tiempos de carga prácticamente nulos, excelente SEO y envío nulo de JavaScript innecesario al cliente.

## 🛠️ Tecnologías Utilizadas

- **Framework Principal**: [Astro v6](https://astro.build/) - Para la generación de sitios web estáticos ultrarrápidos y arquitectura de islas.
- **Estilos**: [Tailwind CSS v4](https://tailwindcss.com/) - Implementado vía Vite para un estilizado de clases utilitarias, rápido y altamente mantenible.
- **Lenguaje**: TypeScript - Tipado estricto para mayor escalabilidad y mejor experiencia del desarrollador (DX).
- **Procesamiento de Imagen**: Integración de optimización nativa de recursos gráficos usando la librería **Sharp**.

## 🚀 Instalación y Desarrollo Local

Sigue estos sencillos pasos para levantar el entorno de desarrollo y realizar modificaciones localmente:

1. **Clona el repositorio** en tu ordenador:
   ```bash
   git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   cd casino
   ```

2. **Instala las dependencias necesarias** usando tu gestor de paquetes favorito (el proyecto utiliza `pnpm` por defecto):
   ```bash
   pnpm install
   # Alternativas si no usas pnpm:
   # npm install o yarn install
   ```

3. **Inicia el servidor local de desarrollo**:
   ```bash
   pnpm run dev
   ```

4. **Visualiza el proyecto**: Abre tu navegador y visita `http://localhost:4321`. Cualquier cambio de código guardado se refrescará de forma automática en tu pantalla.

## 📦 Scripts de Utilidad

Ejecuta los siguientes comandos en tu terminal desde el directorio principal del proyecto para manejar el ciclo de vida de la aplicación:

| Comando | Descripción |
| :--- | :--- |
| `pnpm run dev` | Inicia el servidor de desarrollo en `localhost:4321` con recarga automática. |
| `pnpm run build` | Compila una versión de producción optimizada minificada en la carpeta `./dist/`. |
| `pnpm run preview` | Levanta un servidor local simulando el entorno de producción al leer el contenido de `./dist/`. |
| `pnpm astro [comando]`| Ejecuta comandos nativos y específicos de la interfaz de línea de comandos (CLI) de Astro. |

## 📁 Estructura del Proyecto

Organización simplificada de los archivos primarios que podrás encontrar en este proyecto:

```text
/
├── public/                 # Archivos estáticos inyectables directos (Favicons, assets sin proceso)
├── src/
│   ├── components/         # Componentes y bloques modulares UI (Navbar, Hero, AffiliateGrid, Footer, etc.)
│   ├── layouts/            # Plantillas globales que proveen la estructura principal HTML
│   ├── pages/              # Mapeo de rutas automáticas manejado por Astro (index.astro)
│   └── styles/             # Hojas de estilo globales (global.css) referenciando Tailwind
├── astro.config.mjs        # Archivo de configuración central de Astro y sus integraciones
├── package.json            # Metadatos del proyecto, scripts vitales y dependencias NPM
└── tsconfig.json           # Reglas base del compilador de TypeScript para tu código fuente
```

## 🌐 Guía de Despliegue (Deploy)

Al usar Astro como base estática, desplegar tu landing page en prácticamente cualquier plataforma de *hosting* es extremadamente intuitivo. El sitio se empaqueta listo para el mundo real.

**Plataformas Fáciles Recomendadas:**
- **Vercel** o **Netlify**: Únicamente conecta o integra tu repositorio de GitHub, y estas plataformas detectarán Astro automáticamente para desplegar en cada nuevo commit.
- **GitHub Pages**: Puedes configurar un *Workflow* usando las GitHub Actions para desplegar el sitio gratuitamente usando tus repos en github sin salir de ahí. Referencia detallada: [Guía de Astro para GitHub Pages](https://docs.astro.build/es/guides/deploy/github/).

---

<p align="center">
  Construido con <a href="https://astro.build">Astro</a> 🚀 para alcanzar un rendimiento inigualable y modernidad en la web.
</p>
