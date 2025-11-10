# Actividad formativa 3. Implementación y evaluación de filtros digitales 

Explicación: Etapa	Descripción

Definición de la señal

Se creó una señal compuesta por tres frecuencias (10, 50 y 120 Hz) con ruido blanco para simular interferencia.

----
Diseño del filtro	

Se utilizaron filtros IIR de tipo Butterworth de cuarto orden, elegidos por su respuesta suave y estable.

----
Aplicación del filtro	

Se aplicó el filtrado con filtfilt() (filtrado hacia adelante y hacia atrás) para evitar desfases.

----
Visualización	

Se graficaron las señales originales y filtradas, además de la respuesta en frecuencia de cada filtro.

----

Resultados esperados

🔹 El filtro pasa bajos eliminará las frecuencias superiores a 30 Hz, dejando la componente de 10 Hz. ↘️

🔹 El filtro pasa altos eliminará las frecuencias menores a 60 Hz, conservando principalmente la de 120 Hz. ↗️

🔹 El filtro pasa banda dejará pasar las frecuencias entre 40 y 100 Hz, conservando principalmente la de 50 Hz. ➡️
