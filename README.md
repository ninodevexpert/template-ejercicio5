# CV Online - Laura Martínez Ruiz

Web estática para visualizar el currículum vitae de forma profesional y moderna.

## Características

- Diseño responsive adaptado a todos los dispositivos (móvil, tablet, escritorio)
- Animaciones CSS suaves y profesionales
- Diseño moderno con gradientes y efectos visuales
- Optimizado para impresión
- Carga rápida (HTML + CSS embebido)

## Estructura de archivos

```
/
├── index.html          # Página principal del CV
├── res/
│   ├── DATA.md        # Datos del currículum
│   └── profileimg.png # Imagen de perfil
└── README.md          # Este archivo
```

## Uso

Simplemente abre el archivo `index.html` en tu navegador web. No requiere servidor ni dependencias adicionales.

### Visualización local

```bash
# Opción 1: Abrir directamente
open index.html

# Opción 2: Usar un servidor local simple (Python)
python3 -m http.server 8000
# Luego visita http://localhost:8000
```

## Características técnicas

- HTML5 semántico
- CSS3 con animaciones y transiciones
- Diseño responsive con media queries
- Gradientes y efectos visuales modernos
- Animaciones de entrada y hover effects
- Estilos de impresión optimizados

## Personalización

Para modificar los datos del CV, edita el archivo `res/DATA.md` y actualiza manualmente el contenido en `index.html`, o modifica directamente las secciones correspondientes en el HTML.

Los colores principales se pueden cambiar editando las variables CSS en `:root` dentro del `<style>` del documento.
