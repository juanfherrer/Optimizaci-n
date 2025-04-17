# Optimizaci-n
optimización multivariable con y sin restricciones. Vamos a usar Python y librerías como NumPy y SciPy para resolver el problema.

Cómo correr el código:
Copia el código en una celda de Google Colab.

Ejecuta la celda para ver los resultados de la optimización y las gráficas de nivel.

Este ejemplo ilustra cómo puedes resolver problemas de optimización con o sin restricciones, utilizando funciones matemáticas simples y herramientas de Python como SciPy para calcular los máximos y mínimos.

Explicación del código:
Función de ingresos: Definimos la función 
𝐼
(
𝑥
,
𝑦
)
I(x,y) para modelar los ingresos en función de las variables 
𝑥
x (educación) y 
𝑦
y (experiencia).

Optimización sin restricciones: Usamos el método opt.minimize() de SciPy para maximizar la función de ingresos sin restricciones. Como SciPy minimiza, usamos la función negativa de ingresos.

Optimización con restricciones: Se agrega una restricción 
𝑥
+
𝑦
=
10
x+y=10 utilizando el parámetro constraints de opt.minimize().

Visualización: Graficamos los resultados de ambas optimizaciones en contornos para mostrar cómo cambia la función y cómo los puntos de máximo se localizan.
