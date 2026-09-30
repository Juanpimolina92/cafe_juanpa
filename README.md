# Café JuanPA

Proyecto final de Desarrollo Web: sitio de una cafetería con espacios para estudiar, programar y compartir ideas.

## Sitio publicado

[Visitar Café JuanPA](https://cafe-juanpa.vercel.app)

## Repositorio

[Ver el código en GitHub](https://github.com/Juanpimolina92/cafe_juanpa)

## Tecnologías

- HTML semántico con títulos, descripciones y palabras clave por página.
- SCSS organizado en partials, con variables, nesting, mixins con parámetros y extend.
- Bootstrap para la navegación responsiva y otros componentes.
- Animaciones propias con transiciones y keyframes, junto con la biblioteca AOS.
- Despliegue en Vercel.

## Páginas

- Inicio.
- Proyectos.
- Nuestra historia.
- Servicios.
- Contacto.

## Estructura del proyecto

```text
index.html
pages/
assets/
scss/
  base/
  components/
  layout/
  utilities/
  main.scss
styles/
  style.css
```

`main.scss` reúne los partials mediante `@use`. El CSS compilado está en `styles/` y las imágenes en `assets/`.

## Uso local

Abrir `index.html` en un navegador, manteniendo las carpetas del proyecto juntas. Se necesita conexión a Internet para cargar Bootstrap, AOS y Google Fonts.

Para recompilar los estilos con Sass instalado:

```bash
sass --no-source-map scss/main.scss styles/style.css
```

## Formulario de contacto

El formulario valida los campos, pero todavía no está conectado a un servicio de envío de consultas.

## Autor

Juan Pablo Molina.
