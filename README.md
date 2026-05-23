# Astro Starter Kit: Conceptos Básicos

```sh
npm create astro@latest -- --template basics
```

>  Panadería La Esperanza

## Características
-  Diseño responsivo con Tailwind CSS
-  Animaciones suaves y experiencia visual
-  Carrito de compras integrado con localStorage
-  Mobile-first approach
-  Accesibilidad WCAG compliant
-  SEO optimizado
-  Integración con Google Maps
-  Integración con WhatsApp para pedidos


## Estructura del Proyecto
```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── Products.astro
│   │   ├── Promotions.astro
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Footer.astro
│   │   └── CartModal.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

Para obtener más información sobre la estructura de carpetas de un proyecto de Astro, consulta [nuestra guía sobre la estructura del proyecto](https://docs.astro.build/en/basics/project-structure/).

## Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acciones                                                      |
| :------------------------ | :-----------------------------------------------------------|
| `npm install`             | Instala las dependencias                                    |
| `npm run dev`             | Inicia el servidor local de desarrollo en `localhost:4321`  |
| `npm run build`           | Compila tu sitio de producción a `./dist/`                  |
| `npm run preview`         | Previsualiza tu compilación localmente, antes de implementar|
| `npm run astro ...`       | Ejecuta comandos de la CLI como `astro add`, `astro check`  |
| `npm run astro -- --help` | Obtiene ayuda para usar la CLI de Astro                     |

## Configuración

### Variables de Entorno
No se requieren variables de entorno para desarrollo local.

### Número de WhatsApp
Ubicado en `src/components/CartModal.astro` (línea 73):
```javascript
const whatsappNumber = "3513884669"; // CORREGIR AQUÍ
```

## Soporte
Para reportar bugs o sugerencias, contactar al equipo de desarrollo.
---
**Última actualización:** 23/05/2026
---

## ¿Quieres saber más?
No dudes en consultar [nuestra documentación](https://docs.astro.build) o [unirte a nuestro servidor de Discord](https://astro.build/chat).