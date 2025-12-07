# ⭐ Estructuras Repetitivas en C

Las estructuras repetitivas permiten **ejecutar un bloque de instrucciones varias veces**, hasta que se cumpla una condición o se alcance un límite. Son esenciales para ciclos, automatización y cálculos repetidos. [13]

---

## 🔹 1. Bucle While

El bucle `while` ejecuta un bloque **mientras la condición sea verdadera**.  
Se usa cuando **no sabemos cuántas veces** se repetirá el ciclo, pero sí conocemos la condición de parada. [13]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int contador = 1;

    while (contador <= 5) {
        printf("Contador: %d\n", contador);
        contador++;
    }

    return 0;
}
```

---

## 🔹 2. Bucle Do…While

A diferencia del `while`, este **siempre ejecuta el bloque al menos una vez**, porque la condición se evalúa **al final** del ciclo.  
Es útil cuando necesitamos **una ejecución mínima garantizada**. [14]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int numero;

    do {
        printf("Ingrese un número positivo: ");
        scanf("%d", &numero);
    } while (numero <= 0);

    printf("Número ingresado: %d\n", numero);

    return 0;
}
```

---

## 🔹 3. Bucle For

El bucle `for` se utiliza cuando conocemos **exactamente cuántas veces** queremos iterar.  
Incluye inicialización, condición e incremento en una misma línea, haciéndolo más compacto. [15]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    for (int i = 1; i <= 10; i++) {
        printf("%d\n", i);
    }

    return 0;
}
```

---
