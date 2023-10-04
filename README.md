# Segunda Práctica de Visión por Computador

### TAREA: Realiza la cuenta de píxeles blancos por filas, determina el máximo para filas y columnas (uno para cada) y muestra el número de valores que superan en cada caso 0.95*máximo.

Para conseguir la cuenta de pixeles blancos por fila y columna, usamos la funcion cv2.reduce en cada una de las dimensiones y mas tarde utilizando un bucle for encontramos el maximo de cada una, además hemos representado visualmente la grafica del recuento de pixeles por fila.


### TAREA: Elige otra imagen, muestra el contenido de alguna de las imágenes resultado de Sobel antes y después de ajustar la escala

En este caso, usaremos la funcion cv2.Sobel para realizar la escala y mostramos el calculo de sobel tanto en horizontal, como en vertical y su combinado.

### TAREA: Asumiendo que quieren mostrar a personas que no forman parte del curso de VC el comportamiento de una o varias funcioens de las vistas hasta este momento aplicadas sobre la entrada de la webcam. ¿Cuál(es) escogerían?

En nuestro caso hemos escogido el pop-art de la practica anterior debido a su gran llamativo visual y por otro lado la eliminacion de fondo también debido a que creemos que es lo que mas interes podria levantar.

### TAREA: Tras ver los vídeos My little piece of privacy, Messa di voce y Virtual air guitar propongan (los componentes de cada grupo) una reinterpretación del procesamiento de imágenes con las técnicas vistas o que conozcan.

Para finalizar, hemos creado un filtro que detecta el movimiento comparando los pixeles del frame actual y el anterior para dibujar en el una imagen, en este caso, una nube.
