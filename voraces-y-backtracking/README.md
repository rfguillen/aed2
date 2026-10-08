# Voraces y backtracking · Optimización

Esta práctica reúne dos problemas que utilizan estrategias de resolución distintas.

## Selección de prendas · Backtracking

`Ejercicio F BA.cpp` selecciona un modelo de cada categoría de prendas para maximizar el gasto sin superar el presupuesto disponible. Explora combinaciones mediante backtracking y descarta ramas que no pueden completar una selección válida con el dinero restante.

La entrada incluye el número de casos, el presupuesto, el número de categorías y los precios de sus modelos. La salida indica el gasto encontrado o que no existe solución.

## Emparejamiento de alumnos · Algoritmo voraz

`Ejercicio I AR.cpp` forma parejas utilizando dos matrices: amistad y trabajo. Para cada pareja combina las valoraciones en ambos sentidos y calcula un beneficio; después elige repetidamente la mejor pareja disponible. Si el número de alumnos es impar, queda un alumno sin pareja.

La salida muestra el beneficio acumulado y las parejas, con índices de alumnos que comienzan en 0. Se trata de una estrategia voraz: una elección local favorable no garantiza el mejor emparejamiento global.

## Compilación

```bash
g++ -std=c++11 "Ejercicio F BA.cpp" -o prendas
g++ -std=c++11 "Ejercicio I AR.cpp" -o parejas
```

Ejecuta cada programa por separado y proporciona la entrada correspondiente. Consulta la [memoria de la práctica](Memoria%20Voraces%20y%20Backtracking.pdf) para el análisis y los ejemplos originales.

[Volver a AED2](../README.md)
