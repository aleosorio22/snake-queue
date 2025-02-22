#ANALISIS SNAKE

El código del juego de Snake no usa una estructura de datos de cola como tal, pero su comportamiento es similar en algunos aspectos. La serpiente se maneja con un array donde la cabeza se agrega al inicio con unshift() y la cola se elimina con pop().

La diferencia con una cola real es que en una cola los elementos se agregan al final y se eliminan del frente (FIFO), mientras que aquí la cabeza se agrega al inicio. Básicamente, el código usa un array de forma eficiente para simular el movimiento de la serpiente, pero no implementa una estructura de cola como tal.
