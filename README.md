# Analizador Interactivo de Espectro de Atmósferas Exoplanetarias.
Esta es una herramienta web interactiva para explorar el espectro de la atmósfera del exoplaneta VHS1256-1257b, un exoplaneta observado con el telescopio VLT/X-Shooter en Chile. La página web fue desarrollada como recurso educativo para cursos de física, basada en las actividades didácticas de Best & Petrus et al.
### Utilidades de la página web
La página permite explorar cuatro conceptos físicos fundamentales a través de datos astronómicos reales:
#### 1. Espectro observado
#### 2. Cuerpo negro
#### 3. Gravedad superficial
#### 4. Anchura equivalente
### Archivos
index.html -> página de inicio con navegación

Gráfico.html -> herramienta interactiva principal

Explicaciones.html -> marco teórico

parte1.css -> estilos de la página de inicio

parte2.css -> estilos de la herramienta
### Implementación técnica
La herramienta está construida completamente en HTML, CSS y JavaScript. La física originalmente implementada en Python (numpy, scipy, matplotlib) fue traducida a JavaScript puro, y la visualización usa Plotly.js como reemplazo de matplotlib.
### Modo de uso si no desea descargar los archivos
#### 1. Acceder al link proporcionado: https://lealci.github.io/Herramienta-interactiva/
### Modo de uso si desea descargar los archivos.
#### 1. Descargar todos los archivos en una misma carpeta.
#### 2. Abre index.html en cualquier navegador moderno.
### Aclaraciones de uso
#### - Este proyecto ya no requiere descargar y alojar de manera obligatoria los archivos que la componen, sin embargo estos se pueden descargar si el usuario lo desea.
#### - No requiere instalación ni conexión a internet (excepto para cargar Plotly.js).
#### - El uso del sitio web no necesita componentes de hardware mínimos, solamente los que requiere por naturaleza el uso del navegador en el que se abrirá.
