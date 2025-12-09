# 📘 Portafolio – Unidad de Estructuras de Control

## 📌 1. Estructuras Condicionales

Las estructuras condicionales son instrucciones que controlan el flujo de un programa. Se utilizan para que el software pueda evaluar expresiones lógicas y decidir qué acciones ejecutar en función de si la condición es verdadera o falsa [1]

### ✔️ Tipos de estructuras condicionales
- `if`
  
Es una instrucción condicional que permite ejecutar un bloque de código únicamente si una condición lógica se cumple es verdadera. Si la condición no se cumple, el bloque se omite y el programa continúa con la siguiente instrucción.

- `if – else`

Es una instrucción condicional que permite ejecutar un bloque de código si una condición es verdadera y otro bloque diferente si la condición es falsa. Es decir, ofrece dos caminos alternativos en el flujo de un programa .
  
- `switch`

Es una instrucción condicional que permite evaluar una variable contra múltiples valores posibles y ejecutar el bloque de código asociado al valor que coincida. Es más ordenada y legible que usar muchos if – else consecutivos, especialmente cuando se trabaja con valores discretos como enteros, caracteres o cadenas [2].

---

### ✔️ Ejercicios (Diagrama de flujo y en C)

---

### **Ejercicio 1: Determinar si un número es positivo o negativo**

- A continuacion incluyo un ejersicio que verifica si un numero es positivo o negativo usando estructuras condicionales. 

### Diagrama de flujo:

imagen 1

<img width="1079" height="684" alt="image" src="https://github.com/user-attachments/assets/bee99ad0-056c-4259-b02b-e091d204c7b6" />

### Código en C:

imagen 2 

<img width="467" height="357" alt="image" src="https://github.com/user-attachments/assets/abab25f8-e332-4286-afc3-44f6f5dbc18e" />


### **Ejercicio 2: Calificacion de nota**

- Asi mismo usando estructuras condicionales podemos calificar notas, si es mayor a 7 aprobado y si es menor reprobado. 

### Diagrama de flujo: 

imagen 3 

<img width="535" height="630" alt="image" src="https://github.com/user-attachments/assets/b1eb35ba-4f26-4fcc-acc2-b62fb79f8df5" />

### Código en C:

imagen 4

<img width="454" height="366" alt="image" src="https://github.com/user-attachments/assets/b0d2a5a0-2d37-4dff-a751-23a360b8f2c5" />

## 📌 1. Estructuras repititivas 

Las estructuras repetitivas, también llamadas bucles, son herramientas que permiten la ejecución automática y repetida de una o más instrucciones sin necesidad de escribirlas múltiples veces [5]

✔️ Tipos

- `for`
  
Es una instrucción repetitiva que permite ejecutar un bloque de código un número determinado de veces. Se utiliza cuando se conoce de antemano cuántas iteraciones se deben realizar, ya que integra en una sola línea la inicialización de la variable de control, la condición de repetición y el incremento/decremento.

- `While`

Es una instrucción repetitiva que permite ejecutar un bloque de código mientras una condición lógica sea verdadera. Se utiliza cuando no se sabe de antemano cuántas veces se repetirá el ciclo, ya que depende de la evaluación continua de la condición.

- `do while`

Es una instrucción repetitiva que permite ejecutar un bloque de código al menos una vez, y luego repetirlo mientras la condición lógica se mantenga verdadera. La diferencia principal con while es que la condición se evalúa después de ejecutar el bloque, garantizando así una primera ejecución [3].

  
### **Ejercicio 1, for: Imprimir números del 1 al 10**

En este ejersicio se uso estructuras repititivas para contar de luno al 10. 

### Diagrama de flujo:

imagen 5 

<img width="572" height="534" alt="image" src="https://github.com/user-attachments/assets/8846a9d7-9e50-45c0-8875-d2af5311d523" />

### Código en C:

imagen 6

<img width="421" height="216" alt="image" src="https://github.com/user-attachments/assets/bda2e18d-884d-4a2e-a2d4-a20183695ac8" />

### **Ejercicio 2, while: Sumar números hasta que el usuario ingrese 0**

-En este ejersicio se suman los numero usando la estructura while y si se ingresa el 0 el programa finaliza la ejecución. 


### Diagrama de flujo:

imagen 7

<img width="379" height="686" alt="image" src="https://github.com/user-attachments/assets/28bf761f-5456-4583-b224-237500afb91a" />

### Código en C:

imgen 8

<img width="540" height="386" alt="image" src="https://github.com/user-attachments/assets/aa28b735-cf5f-42c2-b721-c586ff77697c" />

### **Ejercicio 3, do while: Contar del 1 al 15** 

### Diagrama de flujo:

imagen 9

<img width="481" height="596" alt="image" src="https://github.com/user-attachments/assets/b5382743-42d7-4b85-baec-e6ecb49cb523" />

### Código en C:

imagen 10 

<img width="358" height="377" alt="image" src="https://github.com/user-attachments/assets/f6803db2-8370-495b-bebe-a5ba64c066c7" />



## 📌3. Ejercicio Integrador (Condicional + Repetitiva)

### ✔️ Descripción del problema

Crear un programa que pida una contraseña al usuario. Tendrá 3 intentos.
Si acierta: "Acceso permitido"
Si falla 3 veces: "Cuenta bloqueada"


### Diagrama de flujo:

imagen 11

<img width="724" height="705" alt="image" src="https://github.com/user-attachments/assets/831676dd-1ded-4f34-ade4-aded6e68ecba" />

### Phyton:

imagen 12 

<img width="790" height="429" alt="image" src="https://github.com/user-attachments/assets/ed0b133f-1a8d-40ae-b48e-047caeb7cb9d" />

**✔️ Verificación** 

| Prueba | Entrada               | Resultado esperado |
| ------ | --------------------- | ------------------ |
| 1      | 1234                  | Acceso permitido   |
| 2      | 0000, 1111, 2222      | Cuenta bloqueada   |
| 3      | incorrecta → correcta | Acceso permitido   |

## 📌 4. Principales dificultades encontradas

Comprender condicionales anidados.

Seleccionar entre for, while o do–while.

Evitar ciclos infinitos por mala actualización de variables.

## 📌 5. Reflexión crítica de aprendizaje

La unidad permitió fortalecer el razonamiento lógico, traduciendo problemas reales a diagramas y luego a código.
Se evidenció la necesidad de practicar más ejercicios que combinen estructuras condicionales y repetitivas, ya que constituyen la base para algoritmos más avanzados como búsqueda, ordenamiento y manejo de datos.

## 📌 6. Tareas entregadas

### ✔️ APE

### APE 1. Aplicación de estructuras condicionales en la resolución de problemas

https://drive.google.com/file/d/1FCVSOd8DZRS7GYHZaome7Cp6RhmOKG0o/view?usp=drive_link

### APE 2. Aplicación de estructuras condicionales en la resolución de problemas

https://drive.google.com/file/d/1YBD4tNOfzSDXQy-vf0c-QGRjpq5qNRe2/view?usp=drive_link

### ✔️ AA

### AA 1. Diferencias entre los tipos de estructuras condicionales

https://drive.google.com/file/d/1o5vitMPxmFPQyI-HhqexjTzUY-uKzNnG/view?usp=sharing

### AA 2. Cuadro comparativo entre las estructuras repetitivas

https://drive.google.com/file/d/1QUWhrvEcJBnGVRTjCWUJvYK_8kRvMKlj/view?usp=sharing

### Portafolio

https://drive.google.com/file/d/1zMa-Ggl0gTF5aTuobaMlC5uoO7vj8DVe/view?usp=sharing

---

<p align="center">
  <a href="index.md">inicio</a>
</p>



