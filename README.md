# 🐍 Análisis del Código de Snake

El código del juego de **Snake** no usa una estructura de datos de **cola** como tal, pero su comportamiento es similar en algunos aspectos.  

✅ La serpiente se maneja con un **array**, donde:  
- La cabeza se **agrega al inicio** con `unshift()`.  
- La cola se **elimina con `pop()`**.  

⚠️ **Diferencia con una cola real:**  
En una **cola (FIFO)**, los elementos se **agregan al final** y **se eliminan del frente**, mientras que aquí la cabeza se agrega **al inicio**.  

📌 **Conclusión:**  
El código usa un array de forma eficiente para simular el movimiento de la serpiente, pero **no implementa una estructura de cola real**. 🎯  
