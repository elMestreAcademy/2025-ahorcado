# **Proyecto: Juego del Ahorcado - Desarrollando Funcionalidad Incremental**

#### **Objetivo del proyecto:**

Crear un juego de **Ahorcado** que permita a los jugadores adivinar palabras ocultas, comenzando con una versión básica y añadiendo funcionalidad incremental hasta llegar a una versión más completa que incluya gráficos ASCII de los diferentes estados del juego.

---

### **Etapa 1: Juego Básico con Palabras**

**Objetivo:** Implementar el juego básico de ahorcado, sin gráficos ni pistas visuales. El jugador debe adivinar una palabra letra por letra.

1. **Descripción:**
   - El juego debe seleccionar una palabra al azar de una lista predefinida.
   - El jugador debe ingresar letras y el programa debe mostrar las letras correctas y ocultar las incorrectas con guiones bajos (`_`).
   - El jugador tiene un número limitado de intentos para adivinar la palabra (por ejemplo, 6 intentos).
   - Si el jugador adivina todas las letras antes de que se acaben los intentos, gana. Si se quedan sin intentos, pierde.

2. **Requerimientos:**
   - El juego debe ser jugado en la consola o terminal.
   - Mostrar la palabra como una serie de guiones bajos (`_`) al principio.
   - Permitir que el jugador ingrese letras una por una.
   - Mostrar las letras correctas en sus posiciones y las incorrectas como un contador de intentos fallidos.

---

### **Etapa 2: Agregar Indicador de Intentos**

**Objetivo:** Mejorar la interfaz del juego mostrando un contador de intentos fallidos.

1. **Descripción:**
   - Después de cada intento, se debe mostrar al jugador cuántos intentos le quedan.
   - Al final de cada turno, el número de intentos debe reducirse según las letras incorrectas.
   - Si el jugador se queda sin intentos antes de adivinar la palabra, debe perder el juego.

2. **Requerimientos:**
   - Implementar un contador de intentos restantes.
   - Mostrar un mensaje indicando si el jugador ha ganado o perdido al final del juego.
   
---

### **Etapa 3: Agregar Dibujos ASCII para los Estados del Ahorcado**

**Objetivo:** Visualizar los diferentes estados del juego utilizando gráficos ASCII.

1. **Descripción:**
   - Implementar los seis estados del juego del ahorcado con gráficos ASCII que se muestren conforme el jugador comete errores.
   - Los estados deben reflejar cómo va "apareciendo" la figura del ahorcado (cabeza, cuerpo, brazos, piernas).
   - Mostrar el gráfico ASCII en cada intento fallido.

2. **Requerimientos:**
   - Crear una función que imprima el estado correspondiente del ahorcado.
   - Mostrar el gráfico después de cada intento fallido.
   - Los estados del ahorcado deben incrementarse con cada intento erróneo (es decir, cabeza, cuerpo, brazos, piernas).
   - El dibujo debe estar claro y reflejar la progresión del juego.

---

### **Etapa 4: Agregar Funcionalidad de Repetición**

**Objetivo:** Permitir que el jugador juegue múltiples rondas sin reiniciar el programa.

1. **Descripción:**
   - Una vez que un jugador gane o pierda, ofrecerle la opción de jugar otra ronda.
   - Si el jugador decide jugar otra ronda, el juego debe reiniciarse con una nueva palabra aleatoria y un nuevo contador de intentos.

2. **Requerimientos:**
   - Implementar un bucle que permita al jugador jugar varias rondas sin necesidad de reiniciar el programa.
   - Al finalizar cada ronda, preguntar al jugador si desea jugar nuevamente.

---




### **Evaluación:**

- El proyecto se evaluará con base en:
   1. **Correcta implementación de cada funcionalidad.**
   2. **El uso apropiado de funciones y estructuras de control.**
   3. **La claridad y organización del código.**
   4. **La creatividad y adición de funcionalidades adicionales (opcional).**

---

### **Consejos para el desarrollo:**
- Comienza con un enfoque simple, asegurándote de que cada parte funcione correctamente antes de pasar a la siguiente.
- Usa funciones para organizar tu código de forma modular.
- Revisa cómo se muestra el estado del juego después de cada error para asegurarte de que los dibujos sean correctos.

---

**¡Diviértete programando y mejora el juego poco a poco!**

