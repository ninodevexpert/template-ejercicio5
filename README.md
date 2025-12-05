# Currículum Vitae Web - Laura Martínez Ruiz

Sitio web estático profesional y moderno para mostrar el currículum vitae, diseñado con HTML, CSS y JavaScript vanilla.

## Características

- **Diseño Responsive**: Adaptado a todos los dispositivos (móviles, tablets y desktop)
- **Animaciones CSS**: Efectos suaves y profesionales al hacer scroll
- **Navegación Suave**: Scroll suave entre secciones
- **Diseño Moderno**: Interfaz limpia y profesional con gradientes y sombras
- **Optimizado**: Código limpio y eficiente sin dependencias externas

## Estructura del Proyecto

```
/
├── index.html      # Estructura HTML principal
├── styles.css      # Estilos y animaciones CSS
├── script.js       # Interactividad JavaScript
├── data/           # Datos del CV (fuente)
│   └── cv.md
└── README.md       # Este archivo
```

## Uso

Simplemente abre el archivo `index.html` en tu navegador web. No se requiere ningún servidor o instalación adicional.

### Opciones de visualización:

1. **Abrir directamente**: Haz doble clic en `index.html` para abrirlo en tu navegador predeterminado
2. **Servidor local**: Si prefieres usar un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (http-server)
   npx http-server
   
   # Con PHP
   php -S localhost:8000
   ```
   Luego visita `http://localhost:8000` en tu navegador

## Secciones Incluidas

- **Hero**: Presentación principal con animaciones
- **Sobre mí**: Información de contacto y datos personales
- **Experiencia**: Timeline de experiencia profesional
- **Formación**: Educación académica y cursos
- **Habilidades**: Tecnologías y herramientas dominadas
- **Otros Datos**: Información adicional de interés
- **Contacto**: Formas de contacto y redes sociales

## Personalización

Para personalizar el contenido, edita el archivo `index.html` y modifica las secciones correspondientes.

Para cambiar los colores y estilos, modifica las variables CSS en `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... más variables */
}
```

## Compatibilidad

- Chrome/Edge (últimas versiones)
- Firefox (últimas versiones)
- Safari (últimas versiones)
- Navegadores móviles modernos

## Notas

- Las animaciones respetan la preferencia del usuario por movimiento reducido (`prefers-reduced-motion`)
- El diseño es completamente responsive y se adapta automáticamente al tamaño de pantalla
- No se requieren dependencias externas, solo HTML, CSS y JavaScript vanilla
