# PawTinder – Práctica 6: Multimedia adaptativo

Este repositorio forma parte de las prácticas de M09.  
Aquí trabajo una landing page llamada **PawTinder**, pensada para fomentar la adopción responsable de perritos y la participación en acciones solidarias (donaciones, voluntariado, intercambio de juguetes, etc.).

La práctica 6 se centra en hacer que las imágenes y el vídeo sean adaptativos y mejoren la experiencia en distintos tamaños de pantalla.

---

## Enlaces
- GitHub Pages (versión publicada): https://tully0206.github.io/practica4-pawtinderCare/

Para esta práctica estoy usando la rama `practica-06` como base de la versión que se ve en GitHub Pages.

---

## Ejercicio 6.1 – Imágenes y vídeo adaptativos

En el CSS he añadido una regla global para que **todas las imágenes y vídeos** se escalen de forma proporcional dentro de su contenedor:

```css
img,
video {
  max-width: 100%;
  height: auto;
  display: block;
}
