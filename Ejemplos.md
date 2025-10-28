# 🔹 Ejemplos de Algoritmos Secuenciales

## 1️⃣ Calcular el promedio de 4 notas

**📝Pseudocódigo (PSeInt)**  
Algoritmo PromedioNotas  
 Definir nota1, nota2, nota3, nota4, promedio Como Real  
 
 //Datos de entrada
 
 Escribir "Ingrese la primera nota:"  
 Leer nota1  
 Escribir "Ingrese la segunda nota:"  
 Leer nota2  
 Escribir "Ingrese la tercera nota:"  
 Leer nota3  
 Escribir "Ingrese la cuarta nota:"  
 Leer nota4  
 
 //Proceso

 
 promedio <- (nota1 + nota2 + nota3 + nota4) / 4  
 
 //Salida
 
 Escribir "El promedio es:", promedio  
FinAlgoritmo  

**🖥️Código en C**  
#include <stdio.h>  
int main() {  
 float nota1, nota2, nota3, nota4, promedio; 
 
 //Datos de entrada
 
 printf("Ingrese la primera nota: ");  
 scanf("%f", &nota1);  
 printf("Ingrese la segunda nota: ");  
 scanf("%f", &nota2);  
 printf("Ingrese la tercera nota: ");  
 scanf("%f", &nota3);  
 printf("Ingrese la cuarta nota: ");  
 scanf("%f", &nota4);  
 
 //Proceso
 
 promedio = (nota1 + nota2 + nota3 + nota4) / 4;  
 
 //Salida
 
 printf("El promedio es: %.2f\n", promedio);  
 return 0;  
}  

---

## 2️⃣ Calcular el área y perímetro de un rectángulo

**📝Pseudocódigo (PSeInt)**  
Algoritmo AreaPerimetroRectangulo  
 Definir base, altura, area, perimetro Como Real  
 
 //Datos de entrada
 
 Escribir "Ingrese la base del rectángulo:"
 Leer base  
 Escribir "Ingrese la altura del rectángulo:"  
 Leer altura  
 
 //Proceso
 
 area <- base * altura  
 perimetro <- 2 * (base + altura) 
 
 //Salida
 
 Escribir "El área del rectángulo es:", area  
 Escribir "El perímetro del rectángulo es:", perimetro  
FinAlgoritmo  

**🖥️Código en C**  
#include <stdio.h>  
int main() {  
 float base, altura, area, perimetro;  
 
 //Datos de entrada
 
 printf("Ingrese la base del rectangulo: ");  
 scanf("%f", &base);  
 printf("Ingrese la altura del rectangulo: ");  
 scanf("%f", &altura);  
 
 //Proceso
 
 area = base * altura;  
 perimetro = 2 * (base + altura);  
 
 //Salida
 
 printf("El area del rectangulo es: %.2f\n", area);  
 printf("El perimetro del rectangulo es: %.2f\n", perimetro);  
 return 0;  
}  
