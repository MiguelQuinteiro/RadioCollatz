# RadioCollatz 🌀🔢

Este repositorio explora la **Conjetura de Collatz** (también conocida como el problema $3n+1$) mediante representaciones geométricas en coordenadas polares. El proyecto busca identificar patrones visuales en las trayectorias de granizo (*hailstone numbers*) al asignarles una componente radial y angular.

## 🔬 Enfoque de la Investigación

La Conjetura de Collatz dicta que, para cualquier número entero positivo, si es par se divide entre 2 y si es impar se multiplica por 3 y se suma 1, llegando eventualmente al ciclo $1$. En este módulo, cada paso de la secuencia se traduce en una posición espacial:

* **Mapeo Radial**: El valor de $n$ en cada iteración determina la distancia al origen (radio).
* **Mapeo Angular**: El número de paso o una función del valor de $n$ determina el ángulo en radianes.
* **Visualización de Atractores**: Análisis de cómo todas las trayectorias, sin importar su origen, "colapsan" hacia el centro geométrico del gráfico.

## 📁 Estructura del Repositorio

Organizado para el análisis de sistemas dinámicos:

* **src/**: 
  * Algoritmos en Visual Basic 6 para generar secuencias de Collatz de forma masiva.
  * Funciones de conversión de la trayectoria a coordenadas $(r, \theta)$ y $(x, y)$.
* **docs/**: Notas sobre la longitud de la órbita, el valor máximo alcanzado y la estética fractal de las trayectorias.
* **results/**: Visualizaciones de "árboles de Collatz" y gráficos de dispersión radial.

## 🚀 Propósito

El objetivo es encontrar regularidades en el comportamiento aparentemente caótico de la conjetura, utilizando la geometría como herramienta para detectar estructuras que en formato numérico pasan desapercibidas.

---
*Investigación desarrollada por Miguel Quinteiro - Especialista en Modelado Matemático y Arquitecturas de IA.*
