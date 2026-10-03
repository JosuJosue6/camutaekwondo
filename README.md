# CAMU Landing Page

## Overview

Landing editorial en español para CAMU Taekwondo. Presenta los principios del club, información de sedes, galería, entrenamiento, instructores y contacto, con prioridad a la solicitud de una clase demo.

## Tech Stack

Vue 3, Vite, TypeScript y Composition API. No requiere Vue Router ni librerías de iconos o animación.

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Production Build

```bash
npm run build
npm run preview
```

## Project Structure

- `src/components`: secciones y navegación
- `src/data`: principios, sedes, instructores, galería y configuración de imágenes
- `src/styles`: variables, estilos globales y animaciones
- `docs`: documentación de decisiones, secciones y mejoras
- `.agents`: contexto de continuidad para agentes

## Content Management

Modifica los arrays de `src/data/` para ajustar horarios, perfiles y galería. Los datos faltantes permanecen marcados `[POR DEFINIR]`. El PDF `Pagina.pdf` está en la raíz; los datos incluidos en el prompt se reflejan en la web. Revisa textos institucionales contra el PDF antes de reemplazar placeholders.

## Images

Las imágenes editoriales están centralizadas en `src/data/media.ts`, `src/data/gallery.ts` y `src/data/instructors.ts`. Actualmente usan imágenes remotas temporales de Unsplash. Sustituirlas por fotografías CAMU optimizadas en `public/images/` antes de publicar.

## Design System

Consulta `.agents/design-system.md`. El sistema usa carbón, blanco cálido y lima, con Barlow Condensed para titulares y DM Sans para lectura.

## AI Agent Context

Antes de modificar el proyecto, un agente debe leer todos los archivos indicados en `AGENTS.md`, incluido `.agents/continuation.md`.

## Future Development

Validar contenidos institucionales y ubicaciones con CAMU, reemplazar imágenes temporales, conectar el formulario a un servicio real y confirmar los enlaces de redes sociales.

# AI DEVELOPMENT

Antes de modificar el proyecto, leer:

```text
.agents/project-context.md
.agents/architecture.md
.agents/design-system.md
.agents/content.md
.agents/coding-rules.md
.agents/continuation.md
```
