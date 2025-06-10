# Trabajo Práctico: Algoritmos de Ordenamiento en Python

Este proyecto implementa y analiza diferentes algoritmos de ordenamiento en Python, utilizando listas de inventarios como ejemplo práctico. Los algoritmos implementados son **Bubble Sort** y **Selection Sort**, aplicados a listas de diccionarios que representan inventarios de un jugador.

## Contenido

- **Inventarios**: Se definen dos listas de inventarios:
  - Inventario compacto: Contiene 5 elementos.
  - Inventario extendido: Contiene 100 elementos.
- **Algoritmos de Ordenamiento**:
  - **Bubble Sort**:
    - Ordenamiento por cantidad.
    - Ordenamiento por nombre.
  - **Selection Sort**:
    - Ordenamiento por cantidad.
    - Ordenamiento por nombre.
- **Medición de Eficiencia**: Se mide el tiempo de ejecución de cada algoritmo para evaluar su rendimiento.

## Archivos

- `ejercicios_ordenamiento.py`: Contiene la implementación de los algoritmos de ordenamiento y las funciones auxiliares para mostrar los resultados.

## Algoritmos Implementados

### Bubble Sort
Bubble Sort es un algoritmo de ordenamiento que compara pares adyacentes y los intercambia si están en el orden incorrecto. Se utiliza para ordenar los inventarios por:
- **Cantidad**: Ordena los elementos según el número de unidades disponibles.
- **Nombre**: Ordena los elementos alfabéticamente.

### Selection Sort
Selection Sort es un algoritmo que selecciona el elemento más pequeño (o más grande) en cada iteración y lo coloca en su posición correcta. Se utiliza para ordenar los inventarios por:
- **Cantidad**: Ordena los elementos según el número de unidades disponibles.
- **Nombre**: Ordena los elementos alfabéticamente.

## Funciones Principales

### `bubble_sort_por_cantidad(inventario)`
Ordena una lista de diccionarios por el campo `cantidad` utilizando Bubble Sort.

### `bubble_sort_por_nombre(inventario)`
Ordena una lista de diccionarios por el campo `nombre` utilizando Bubble Sort.

### `selection_sort_por_cantidad(inventario)`
Ordena una lista de diccionarios por el campo `cantidad` utilizando Selection Sort.

### `selection_sort_por_nombre(inventario)`
Ordena una lista de diccionarios por el campo `nombre` utilizando Selection Sort.

### `mostrar_inventario(inventario, estado)`
Imprime el inventario en la consola con un encabezado descriptivo.

## Ejecución

Para ejecutar el proyecto, simplemente corre el archivo `ejercicios_ordenamiento.py`. El programa mostrará los inventarios ordenados por cantidad y por nombre, junto con el tiempo de ejecución de cada algoritmo.

## Ejemplo de Salida

```plaintext
--- INVENTARIO (ORDENADO POR CANTIDAD) ---
15 unidades: Gema
50 unidades: Hierro
100 unidades: Piedra
320 unidades: Oro
650 unidades: Madera
