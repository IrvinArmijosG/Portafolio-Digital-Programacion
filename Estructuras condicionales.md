# ⭐ Estructuras Condicionales en C

Las estructuras condicionales permiten **tomar decisiones** dentro de un programa según el valor de una condición lógica. Son fundamentales para controlar el flujo del software y decidir qué bloque de código se ejecuta. [9]

---

## 🔹 1. If Simple

La estructura `if` simple evalúa una condición.  
Si es verdadera (**true**) se ejecuta el bloque; si es falsa (**false**) se ignora. Es útil cuando solo se debe comprobar una condición. [9]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int numero;
    printf("Ingrese un número: ");
    scanf("%d", &numero);

    if (numero > 0) {
        printf("El número es positivo\n");
    }

    return 0;

```
---


## 🔹 2. If – Else

Se utiliza cuando se requiere escoger entre **dos posibles resultados**.  
Si se cumple la condición se ejecuta el primer bloque; si no, el segundo. [10]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int edad;
    printf("Ingrese su edad: ");
    scanf("%d", &edad);

    if (edad >= 18) {
        printf("Eres mayor de edad\n");
    } else {
        printf("Eres menor de edad\n");
    }

    return 0;
}
```

---

## 🔹 3. If – Else If – Else

Se usa cuando existen **múltiples alternativas**.  
Las condiciones se evalúan en orden; la primera verdadera se ejecuta. [11]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int nota;
    printf("Ingrese la nota: ");
    scanf("%d", &nota);

    if (nota >= 90) {
        printf("Excelente\n");
    } else if (nota >= 70) {
        printf("Aprobado\n");
    } else {
        printf("Reprobado\n");
    }

    return 0;
}
---

```
## 🔹 4. Switch – Condicional Múltiple

`Switch` compara una variable contra varios valores posibles (casos).  
Es ideal cuando las opciones son **claras y constantes**, haciendo el código más limpio que muchos `if`. [12]

### ✔ Ejemplo en C
```c
#include <stdio.h>

int main() {
    int opcion;
    printf("1. Suma\n2. Resta\n3. Multiplicación\nSeleccione una opción: ");
    scanf("%d", &opcion);

    switch (opcion) {
        case 1:
            printf("Elegiste suma\n");
            break;
        case 2:
            printf("Elegiste resta\n");
            break;
        case 3:
            printf("Elegiste multiplicación\n");
            break;
        default:
            printf("Opción no válida\n");
            break;
    }

    return 0;
}
