# Portafolio personal

Una primera versión de tu portafolio, hecha con HTML y CSS sin dependencias. Puedes abrir `index.html` en el navegador para verla.

## Personalizar

Empieza por `index.html`:

1. Actualiza el texto de presentación y la sección «Sobre mí» cuando quieras contar más de tu historia.
2. Reemplaza `tu-email@ejemplo.com` por tu correo en el enlace de contacto.

## Añadir un proyecto

La sección «Proyectos» ya incluye tarjetas para la calculadora y el formulario, con enlaces directos a sus carpetas en GitHub. Para añadir otro proyecto, duplica un `<article class="project-card">` dentro de `<div class="project-grid">` y cambia el contenido y el enlace:

```html
<article class="project-card">
  <div class="project-visual" aria-hidden="true">
    <!-- Aquí puedes diseñar una ilustración para el proyecto -->
  </div>
  <div class="project-details">
    <p class="eyebrow">TIPO DE PROYECTO</p>
    <h3>Nombre del proyecto</h3>
    <p>Qué hace, qué aprendiste o qué problema resuelve.</p>
    <span class="project-tag">Tecnología o asignatura</span>
    <a class="project-link" href="URL_DEL_REPOSITORIO" target="_blank" rel="noopener noreferrer">
      Ver código en GitHub <span aria-hidden="true">↗</span>
    </a>
  </div>
</article>
```

Puedes añadir una tarjeta por proyecto y ajustar su apariencia en `styles.css`. Para practicar sin publicar cambios, edita el contenido y abre de nuevo `index.html` en el navegador.
