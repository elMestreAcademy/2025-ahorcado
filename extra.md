# **Etapa Extra: Jugar Contra la Máquina**

**Objetivo:** Permitir que el jugador juegue contra la máquina, donde la máquina elige la palabra y el jugador intenta adivinarla.

---

## **1. Descripción:**

- La máquina seleccionará una palabra aleatoria de una lista predefinida o desde un archivo de texto.
- El jugador deberá adivinar la palabra letra por letra.
- Al igual que en las etapas anteriores, el jugador tendrá un número limitado de intentos para adivinar la palabra antes de que el juego termine.
- La máquina debe mostrar los estados del ahorcado de acuerdo con los intentos fallidos del jugador (como se vio en la Etapa 3).

---

## **2. Requerimientos:**

1. **Generación aleatoria de la palabra:**
   - La máquina debe seleccionar una palabra aleatoria de una lista predefinida o desde un archivo de texto.

2. **Interacción del jugador:**
   - El jugador debe poder adivinar las letras de la palabra elegida por la máquina.
   - El juego debe seguir los mismos principios que en las etapas anteriores (mostrar la palabra oculta con guiones bajos, mostrar intentos fallidos, etc.).

3. **Mostrar el progreso del juego:**
   - A medida que el jugador adivine letras correctamente, la palabra se debe actualizar mostrando las letras correctas.
   - Si el jugador comete un error, debe ver el dibujo del ahorcado correspondiente.

4. **Fin del juego:**
   - Si el jugador adivina la palabra antes de que se acaben los intentos, gana.
   - Si el jugador se queda sin intentos, pierde. En este caso, se debe mostrar la palabra correcta.

5. **Repetir el juego:**
   - Después de que el jugador gane o pierda, se le debe dar la opción de jugar otra ronda.
   - La máquina debe elegir una nueva palabra cada vez que inicie una nueva ronda.

---

## **3. Funcionalidades adicionales (opcional):**

1. **Pistas de la máquina (opcional):**
   - La máquina puede ofrecer una pista al jugador si lo solicita, como la categoría de la palabra (por ejemplo, "animal", "fruta", "objeto", etc.).

2. **Palabras más difíciles:**
   - La máquina puede seleccionar palabras de diferentes niveles de dificultad, que puede ser configurado al inicio del juego.

3. **Número de intentos ajustables (opcional):**
   - Se puede agregar la opción para que el jugador elija cuántos intentos tendrá, lo que cambia la dificultad del juego.

---

## **4. Ejemplo de Flujo de Juego:**

- **Inicio del juego:** La máquina selecciona una palabra aleatoria (por ejemplo, "elefante").
- **Progreso del juego:**
    - El jugador ve una serie de guiones bajos: `_ _ _ _ _ _ _ _`
    - El jugador adivina la letra "e". La máquina actualiza la palabra a: `e _ e _ _ e _ e`
    - El jugador adivina la letra "t". La máquina actualiza la palabra a: `e _ e _ t e _ e`
    - El jugador adivina la letra "l". La máquina actualiza la palabra a: `e l e _ t e _ e`
    - El jugador comete un error y adivina "a". La máquina muestra el primer estado del ahorcado.
    - Y el proceso continúa hasta que el jugador gane o pierda.

---

# **Evaluación:**

- El jugador debe ser capaz de jugar contra la máquina, adivinando la palabra seleccionada por el sistema.
- El juego debe ser interactivo y mostrar las actualizaciones de los intentos y el progreso en el dibujo del ahorcado.
- Se evaluará la correcta implementación de la selección aleatoria de palabras y la interacción fluida entre la máquina y el jugador.

---

¡Con esta etapa, el juego se vuelve mucho más dinámico y divertido, y los estudiantes aprenderán cómo hacer que la máquina sea un oponente desafiante!
