// Tarea del entregable: Figuras terminados...

# Clasificador de Triángulos

Este proyecto es una aplicación web que permite **dibujar triángulos a mano alzada** y clasificarlos automáticamente en diferentes tipos mediante un modelo de aprendizaje automático entrenado en el navegador.

---

## Tecnologías usadas

- [p5.js](https://p5js.org/) — Para la creación y manejo del canvas de dibujo.
- [ml5.js](https://ml5js.org/) — Librería de aprendizaje automático para crear y entrenar un clasificador de imágenes.
- HTML, CSS y JavaScript para la interfaz y lógica.

---

## Descripción

La aplicación carga un conjunto de imágenes preclasificadas de triángulos (acutángulos y triángulos rectángulos con distintas orientaciones) que sirven para entrenar un modelo de red neuronal directamente en el navegador.

El usuario puede:

- Dibujar un triángulo en el canvas.
- Clasificar el triángulo dibujado con el modelo entrenado.
- Visualizar la etiqueta y el porcentaje de confianza de la clasificación.
- Limpiar el canvas para hacer nuevos dibujos.

---

## Cómo usar

1. Abrir el archivo `triangulos.html` en un navegador compatible.
2. Esperar a que se carguen y entrenen las imágenes (esto puede tardar unos segundos).
3. Dibujar un triángulo en el área de dibujo.
4. Pulsar el botón **"Clasificar Triángulo"** para obtener la predicción.
5. Usar el botón **"Limpiar Dibujo"** para borrar el canvas y empezar de nuevo.

---