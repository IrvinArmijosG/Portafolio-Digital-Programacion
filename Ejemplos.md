# 🔹 Ejemplos de Algoritmos Secuenciales
### ⚠️ Análisis del problema

## 1️⃣ Calcular el promedio de 4 notas

**📥 Datos de entrada**  
- 📝 Cuatro valores numéricos que representan las notas: nota1, nota2, nota3, nota4  
- 🔢 Cada nota puede ser decimal y se ingresa por teclado  

**⚙️ Proceso**  
- 🧮 Fórmula: promedio = (nota1 + nota2 + nota3 + nota4) / 4  

**📤 Salida**  
- 🎯 El valor del promedio
## Prueba de escritorio
| nota1 | nota2 | nota3 | nota4 | Operación                  | Promedio |
|-------|-------|-------|-------|---------------------------|----------|
| 7     | 8     | 9     | 10    | (7+8+9+10)/4             | 8.5      |



**📝 Pseudocódigo (PSeInt)**  
Algoritmo PromedioNotas  
 Definir nota1, nota2, nota3, nota4, promedio Como Real  
 
 //📥 Datos de entrada
 
 Escribir "Ingrese la primera nota:"  
 Leer nota1  
 Escribir "Ingrese la segunda nota:"  
 Leer nota2  
 Escribir "Ingrese la tercera nota:"  
 Leer nota3  
 Escribir "Ingrese la cuarta nota:"  
 Leer nota4  
 
 //⚙️ Proceso
 
 promedio <- (nota1 + nota2 + nota3 + nota4) / 4  
 
 //📤 Salida
 
 Escribir "El promedio es:", promedio  
FinAlgoritmo  

**🖥️ Código en C**  
#include <stdio.h>  
int main() {  
 float nota1, nota2, nota3, nota4, promedio; 
 
 //📥 Datos de entrada
 
 printf("Ingrese la primera nota: ");  
 scanf("%f", &nota1);  
 printf("Ingrese la segunda nota: ");  
 scanf("%f", &nota2);  
 printf("Ingrese la tercera nota: ");  
 scanf("%f", &nota3);  
 printf("Ingrese la cuarta nota: ");  
 scanf("%f", &nota4);  
 
 //⚙️ Proceso
 
 promedio = (nota1 + nota2 + nota3 + nota4) / 4;  
 
 //📤 Salida
 
 printf("El promedio es: %.2f\n", promedio);  
 return 0;  
}  

## 💡 Breve explicación
Este código **toma cuatro notas ingresadas por el usuario**, calcula su **promedio** y muestra el resultado en pantalla. 🎯

---

## 2️⃣ Calcular el área y perímetro de un rectángulo

### ⚠️ Análisis del problema

**📥 Datos de entrada**  
- 📝 Dos valores numéricos: base y altura  
- 🔢 Pueden ser decimales y se ingresan por teclado  

**⚙️ Proceso**  
- 🧮 Calcular el área: area = base * altura  
- 📏 Calcular el perímetro: perimetro = 2 * (base + altura)  

**📤 Salida**  
- 🎯 Área y perímetro del rectángulo

## Prueba de escritorio
| base | altura | Operación Área  | Área | Operación Perímetro | Perímetro |
|------|------|--------|----------------|------|-------------------|
| 5    | 3      | 5*3            | 15   | 2*(5+3)           | 16        |


**📝 Pseudocódigo (PSeInt)**  
Algoritmo AreaPerimetroRectangulo  
 Definir base, altura, area, perimetro Como Real  
 
 //📥 Datos de entrada
 
 Escribir "Ingrese la base del rectángulo:"  
 Leer base  
 Escribir "Ingrese la altura del rectángulo:"  
 Leer altura  
 
 //⚙️ Proceso
 
 area <- base * altura  
 perimetro <- 2 * (base + altura) 
 
 //📤 Salida
 
 Escribir "El área del rectángulo es:", area  
 Escribir "El perímetro del rectángulo es:", perimetro  
FinAlgoritmo  

**🖥️ Código en C**  
#include <stdio.h>  
int main() {  
 float base, altura, area, perimetro;  
 
 //📥 Datos de entrada
 
 printf("Ingrese la base del rectangulo: ");  
 scanf("%f", &base);  
 printf("Ingrese la altura del rectangulo: ");  
 scanf("%f", &altura);  
 
 //⚙️ Proceso
 
 area = base * altura;  
 perimetro = 2 * (base + altura);  
 
 //📤 Salida
 
 printf("El area del rectangulo es: %.2f\n", area);  
 printf("El perimetro del rectangulo es: %.2f\n", perimetro);  
 return 0;  
}  

## 💡 Breve explicación
Este código **recibe la base y la altura de un rectángulo**, calcula su **área** y **perímetro**, y luego los muestra en pantalla. 📏🎯

## [Descargar codigos recientemente mostrados](https://github.com/IrvinArmijosG/Portafolio-Digital-Programacion/blob/main/Codigos.zip)

