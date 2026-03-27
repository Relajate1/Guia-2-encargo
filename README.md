# Guía 2 Limpieza y Preprocesamiento de Datos

## Estructura del proyecto

## ⚙️ Pasos realizados

### 1. Carga de datos
- Se lee el archivo `notasdeestudiantes.csv` con Pandas.

### 2. Limpieza de datos
- Normalización de nombres de columnas.
- Eliminación de espacios en texto.
- Estandarización de carreras.
- Conversión de notas a formato numérico.

### 3. Validaciones
- Notas fuera de rango (1.0 a 7.0)
- Verificación de columnas requeridas.

### 4. Procesamiento
- Cálculo de promedio por estudiante.
- Eliminación de duplicados.
- Imputación de valores faltantes con la media.

### 5. Análisis
- Resumen general (total, promedio, min, max).
- Promedio por carrera.

### 6. Ejecución
- Se ejecuta todo desde el notebook (`.ipynb`) importando funciones desde `src`.
