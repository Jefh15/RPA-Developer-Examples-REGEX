# RPA-Developer-Examples-REGEX


# Recapitulemos las actividades y los métodos utilizados:

* Comenzamos el proyecto como Secuencia y usamos una actividad Asignar para una variable recién creada Cadena.

* Usamos el asistente de la actividad Coincidencias para identificar los nombres y números de las calles:

- Se ajustará Tipo como Avanzado
- Se añadirá "carretera", "camino", "avenida" y así sucesivamente en el Valor campo;
- Se utilizará el cuantificador Exactamente con el valor 1;
- Se asegurará de que la casilla Ignorar caso se ha marcado.

* Usamos una actividad Para cada para recorrer la variable de salida de la actividad Coincidencias e imprimirla utilizando una actividad Registrar mensaje.