# Divide y vencerás · Búsqueda de subcadenas

Dada una cadena `A` y un conjunto `S` de cinco caracteres, el programa localiza todas las subcadenas consecutivas de longitud tres cuyos caracteres son distintos entre sí y pertenecen a `S`.

La solución divide la cadena en partes, resuelve los casos pequeños y combina los resultados comprobando las subcadenas que cruzan la frontera entre ambas partes. Las posiciones se presentan comenzando en 1.

## Archivos

- `DyV Ejercicio 7.cpp`: implementación del algoritmo.
- `Generador de Casos.cpp`: generación de cadenas para distintos tamaños y patrones de entrada.
- `Instrucciones de Uso.txt`: instrucciones.
- [Memoria](Memoria%20Divide%20y%20venceras.pdf): explicaciónn y análisis de la práctica.

## Compilación y uso

```bash
g++ -std=c++11 "DyV Ejercicio 7.cpp" -o dyv
g++ -std=c++11 "Generador de Casos.cpp" -o generador
./dyv
```

Introduce la cadena y después los cinco caracteres del conjunto. Por ejemplo, para `abcde` y el conjunto `a b c d e`, las subcadenas válidas empiezan en las posiciones 1, 2 y 3.

El generador se ejecuta de forma independiente con `./generador`; sus archivos permiten preparar entradas para comparar escenarios.

[Volver a AED2](../README.md)
