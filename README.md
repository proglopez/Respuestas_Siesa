# Respuestas_Siesa
Respuestas de prueba técnica Siesa (Desarrollador Estándar)

# Punto 17.Algoritmo y Pseudocódigo
# Algoritmo de división de dos números enteros

Este algoritmo permite dividir dos números enteros y mostrar el resultado de la división. Si el segundo número es cero, se mostrará un mensaje de error indicando que la división por cero no está permitida.

## Tabla de contenido

- [Algoritmo](#algoritmo)
- [Pseudocódigo](#pseudocódigo)

## Algoritmo
Pasos del algoritmo:

1. Inicio.
2. Leer el valor del primer número entero y almacenarlo en una variable `num1`.
3. Leer el valor del segundo número entero y almacenarlo en una variable `num2`.
4. Verificar si el valor de `num2` es cero. Si es cero, mostrar un mensaje de error indicando que la división por cero no está permitida. De lo contrario, continuar con el paso 5.
5. Dividir `num1` entre `num2` y almacenar el resultado en una variable `resultado`.
6. Mostrar el valor de la variable `resultado`.
7. Fin.

## Pseudocódigo
java
Copy code
ALGORITMO division
  INICIO
    LEER num1
    LEER num2
    SI num2 = 0 ENTONCES
      ESCRIBIR "Error: división por cero"
    SINO
      resultado = num1 / num2
      ESCRIBIR resultado
    FIN SI
  FIN
FIN ALGORITMO

