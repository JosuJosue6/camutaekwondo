# Architecture

## Folders

- `src/components`: cada componente representa una sección de página o header/footer.
- `src/data`: contenido repetido tipado por inferencia de TypeScript y configuración central de imágenes.
- `src/composables`: lógica transversal, actualmente la aparición de elementos por IntersectionObserver.
- `src/styles`: tokens CSS, reglas globales y animaciones.
- `public/images`: destino previsto para fotografías locales optimizadas.
- `docs`: decisiones y futuras tareas del proyecto.

## Data flow

Los componentes importan arrays/objetos de `src/data` y recorren esos datos en sus templates. `App.vue` compone las secciones y activa el scroll suave y el composable de reveal.

## Styling and assets

Design tokens y breakpoints viven en `src/styles/variables.css` y `src/styles/globals.css`. Imágenes están configuradas en `src/data/media.ts`, `gallery.ts` e `instructors.ts`; no dispersar URLs por los templates.

## Naming

Componentes Vue en PascalCase; composables `useX`; módulos de datos en camelCase; clases CSS en kebab-case.
