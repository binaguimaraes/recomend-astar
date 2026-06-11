# recomend-astar
Sistema de recomendación en Python que utiliza el algoritmo A* para encontrar el mejor producto según su probabilidad de conversión.

## 📌 Recomendador de Productos con A*
Este proyecto implementa un sistema de recomendación en Python utilizando el algoritmo A\* para encontrar el camino más eficiente entre productos, basándose en su probabilidad de conversión.

## 🚀 Objetivo
Demostrar cómo aplicar el algoritmo A* en un contexto de recomendación, modelando productos como nodos de un grafo y utilizando una heurística que prioriza los productos con mayor probabilidad de conversión.

## 🧠 ¿Cómo funciona?
Cada producto tiene:

nombre

categoría

probabilidad de conversión

El grafo conecta cada producto con todos los demás.

La heurística devuelve el valor negativo de la probabilidad, ya que A* minimiza costos.

El algoritmo busca el camino más prometedor desde un producto inicial hasta uno objetivo.

## 📂 Estructura del proyecto
Producto → clase que representa un producto

RecomendacionAStar → clase que implementa el algoritmo A*

heuristica() → función que evalúa la calidad de un producto

main → ejemplo de uso con productos de prueba

## 📌 Tecnologías utilizadas
Python 3

heapq (cola de prioridad)

## 🤝 Contribuciones
Las contribuciones, sugerencias y mejoras son bienvenidas.
Puedes abrir un issue o enviar un pull request.
