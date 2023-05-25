

// 1. Error de escritura en el nombre del evento: Se escribía "addeventListener" en lugar de "addEventListener", lo cual provocaba que el evento no se registrara correctamente.

// 2. Falta del punto antes de la clase en la selección del elemento: Al seleccionar el elemento con la clase "lowOrHi", faltaba el punto antes de la clase, lo que generaba un error al intentar acceder al elemento.

// 3. Limitación de intentos: El juego solo permitía realizar 5 intentos en lugar de los 10 requeridos. Esto se debía a un error en la comparación dentro del condicional que verifica si se alcanzó el límite de intentos.

// 4. Validación de número entero: No se realizaba una validación adecuada para asegurar que el número ingresado fuera un entero. Se solucionó utilizando la función `parseInt()` para convertir el valor a un número entero y luego verificando si es un número válido mediante `isNaN()` y `Number.isInteger()`.

// 5. Validación de número mayor a 100: No se realizaba una validación para asegurar que el número ingresado no fuera mayor a 100. Se agregó un condicional adicional para mostrar una alerta en caso de que el número fuera mayor a 100.

