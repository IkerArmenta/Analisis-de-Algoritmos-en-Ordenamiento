# **Proyecto de Algoritmos de Ordenamiento y Análisis de Tiempos**

Este proyecto implementa varios algoritmos clásicos de ordenamiento en C++, y mide su rendimiento utilizando arreglos aleatorios. Los tiempos de ejecución se almacenan en archivos CSV generados automáticamente para facilitar el análisis.

## **Algoritmos Implementados**
Los algoritmos de ordenamiento incluidos son:
- **Inserción** (`insercionOrdenada`)
- **Burbuja** (`burbujaOrdenada`)
- **Selección** (`seleccionOrdenada`)
- **Shell** (`shellOrdenado`)
- **Merge Sort** (`mezclaWrapper`)

## **Estructura del Código**
El proyecto incluye:
- **Funciones de Ordenamiento**: Implementación de los algoritmos mencionados.
- **Medición de Desempeño**:
  - `medirDesempeno`: Ejecuta los algoritmos y mide su tiempo de ejecución en nanosegundos.
  - Los resultados se almacenan en archivos CSV.
- **Generación de Números Aleatorios**: Cada prueba utiliza datos generados dinámicamente.
- **Archivo `main.cpp`**: Invoca los algoritmos y almacena los resultados en CSV.

## **Archivos Generados**
Cada algoritmo produce un archivo CSV con los tiempos de ejecución:
- `resultado_insercion.csv` – Resultados del algoritmo de Inserción.
- `resultado_burbuja.csv` – Resultados del algoritmo de Burbuja.
- `resultado_seleccion.csv` – Resultados del algoritmo de Selección.
- `resultado_shell.csv` – Resultados del algoritmo de Shell.
- `resultado_mezcla.csv` – Resultados del algoritmo Merge Sort.

## **Cómo Compilar y Ejecutar**
### **Compilación**
Usa un compilador como `g++` para compilar el archivo principal:
```bash
g++ -o ordenamiento main.cpp -std=c++17
