# Analizador Interactivo de Espectro de Atmósferas Exoplanetarias.
Esta es una herramienta web interactiva para explorar el espectro de la atmósfera del exoplaneta VHS1256-1257b, un exoplaneta observado con el telescopio VLT/X-Shooter en Chile. La página web fue desarrollada como recurso educativo para cursos de física, basada en las actividades didácticas de Best & Petrus et al.
### Utilidades de la página web
La página permite explorar cuatro conceptos físicos fundamentales a través de datos astronómicos reales:
#### 1. Espectro observado
#### 2. Cuerpo negro
#### 3. Gravedad superficial
#### 4. Anchura equivalente
  Adicional a esto, hay una página de explicaciones que aborda la física y el funcionamiento de cada uno de los gráficos.
### Archivos.
index.html -> Página de inicio con navegación

Gráfico.html -> Herramienta interactiva principal

Explicaciones.html -> Marco teórico

parte1.css -> Estilos de la página de inicio

parte2.css -> Estilos de la herramienta

parte3.css -> Estilos de la página de explicaciones

### Implementación técnica
La herramienta está construida completamente en HTML, CSS y JavaScript. La física originalmente implementada en Python (numpy, scipy, matplotlib) fue traducida a JavaScript puro, y la visualización usa Plotly.js como reemplazo de matplotlib.
### Modo de uso.
#### Acceder al link proporcionado: https://lealci.github.io/Herramienta-interactiva/
### Aclaraciones de uso
#### - Este proyecto no requiere descargar y alojar de manera obligatoria los archivos que la componen, sin embargo, los archivos están a libre disposición en caso de que algún usuario y/o docente quiera editar las limitaciones físicas de la herramienta para visualizar otro objeto.
#### - Al ser una página web, solamente se necesita una conexión a internet estable para visualizarla.
#### - El uso del sitio web no necesita componentes de hardware mínimos, solamente los que requiere por naturaleza el uso del navegador en el que se abrirá.
