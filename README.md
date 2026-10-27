# Visuals-to-Disseny-en-Moviment

Una composición gráfica generativa creada con Processing que transforma ondas realizadas con seno y coseno en patrones de puntos en movimiento. A través de la variación del tamaño, la posición y la distribución de los puntos, la pieza explora la relación entre las ondas y las interferencias visuales.

## Qué hace

**Ondas:** genera varias ondas horizontales formadas por puntos que siguen su recorrido.

**Interferencias:** combina distintas ondas para alterar su forma y crear variaciones en el patrón.

**Estética:** utiliza una paleta monocromática y una trama de puntos inspirada en la impresión "medios tonos" y el arte óptico.

## Cómo funciona

La composición se con código en Processing. Los puntos se distribuyen a lo largo del lienzo y siguen el movimiento de varias ondas creadas con las funciones seno y coseno. Los cambios de tamaño y los desplazamientos aleatorios generan distorsiones y hacen que las ondas tengan un aspecto más irregular.

## Parámetros modificables

- **Amplitud:** controla la altura de las ondas.
- **Frecuencia:** modifica la separación y la repetición de las ondas.
- **Espaciado:** determina la densidad de la trama de puntos.
- **Velocidad:** controla el ritmo de la animación.
- **Distorsión:** regula la irregularidad de los puntos y la intensidad de las interferencias.

## Formato

Lienzo vertical de 1080 × 1920 px, con fondo negro y puntos blancos.

## Herramientas

Processing · Código generativo · Animación gráfica

### Referentes de código

**Sine Wave · Processing**  
https://processing.org/examples/sinewave.html

Referencia para la creación de ondas sinusoidales mediante la función `sin()`, tomando como base su estructura y movimiento para generar las ondas de la composición.

**Distance 2D · Processing**  
https://processing.org/examples/distance2d.html

Referencia para trabajar con una retícula de puntos cuyo tamaño varía en función de la distancia. Esta lógica sirve como punto de partida para explorar variaciones en el tamaño de los puntos y su relación con las ondas.
