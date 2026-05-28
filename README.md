# Departlite — Tema Shopify
 
Tema de Shopify desarrollado a medida para una tienda cliente, basado en Dawn (el tema de referencia oficial de Shopify). El tema fue personalizado, desplegado y utilizado en una tienda en producción.
 
---
 
## Sobre el proyecto
 
El cliente requería un tema Shopify adaptado a la identidad visual y necesidades específicas de su tienda. Se tomó Dawn como base — el tema open source de Shopify construido con los principios de Online Store 2.0 — y se personalizó en profundidad: secciones, snippets, plantillas, estilos y configuración de internacionalización.
 
## Stack tecnológico
 
- **Liquid** — lenguaje de plantillas de Shopify (70% del código)
- **CSS** — estilos personalizados
- **JavaScript** — mejoras progresivas
- **Shopify CLI** — desarrollo y despliegue local
- **Theme Check** — linting y validación del tema
## Estructura
 
```
├── assets/        # CSS, JS, imágenes y fuentes
├── config/        # Ajustes y esquemas del tema
├── layout/        # Plantillas base (theme.liquid)
├── locales/       # Traducciones e internacionalización
├── sections/      # Secciones configurables del editor
├── snippets/      # Fragmentos reutilizables
└── templates/     # Plantillas de páginas, productos, colecciones
```
 
## Características
 
- Basado en Online Store 2.0: secciones en todas las páginas
- Soporte multiidioma mediante archivos de localización
- Theme Check integrado para validación de calidad del código
- Personalización completa de secciones desde el editor de Shopify
- Rendimiento optimizado siguiendo la filosofía HTML-first de Dawn
## Desarrollo local
 
```bash
# Instalar Shopify CLI
npm install -g @shopify/cli
 
# Conectar con la tienda y levantar servidor de desarrollo
shopify theme dev --store=tu-tienda.myshopify.com
```
 
## Contexto
 
Este proyecto es representativo del trabajo freelance en e-commerce. Shopify y Liquid tienen su propio ecosistema con convenciones específicas — aprenderlo implicó entender el modelo de datos de Shopify (productos, colecciones, variantes, metafields) y la arquitectura de temas con Online Store 2.0.
 
## Autor
 
**Julio Martínez**
