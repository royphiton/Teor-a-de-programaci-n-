# <p align="center">📘 Portafolio – Modularidad y Arreglos: 

### <p align="center">📌 1.  Modularidad 
La modularidad es un principio de diseño en programación que consiste en dividir un programa en módulos o funciones independientes, cada uno con una responsabilidad específica.

###  ventajas 

🔹 Reutilización: Un módulo puede usarse en distintos programas.

🔹 Mantenimiento: Es más fácil localizar y corregir errores.

🔹 Claridad: El código se entiende mejor al estar organizado en bloques.

🔹 Trabajo en equipo: Diferentes programadores pueden trabajar en distintos módulos sin interferir.

## Por valor: 

En este caso, la función recibe una copia del dato.
Los cambios dentro de la función no afectan la variable original [1].

## Ejemplo: 

La función recibe una copia del número (x).

Dentro de la función, esa copia se modifica (x = 25).

Pero el original (numero = 5) no cambia, porque solo trabajamos con la copia.

Es como si prestaras una fotocopia de tu cuaderno: puedes rayar la copia, pero el cuaderno original sigue intacto. 

imagen 1

<img width="615" height="398" alt="image" src="https://github.com/user-attachments/assets/b2190255-b261-464c-a27b-e389210585a1" />

## Respuesta: 

imagen 2

<img width="443" height="81" alt="image" src="https://github.com/user-attachments/assets/01f0752a-5bba-4244-9294-722fba3e7c4a" />

## Por referencia: 

Aquí la función recibe la dirección de memoria de la variable.
Los cambios dentro de la función sí afectan la variable original [2].

## Ejemplo: 

La función recibe la dirección de memoria del número (&numero).

Dentro de la función, se accede al valor original y se modifica (numero = 25).

Ahora el cambio sí afecta al original, porque trabajamos directamente sobre él.

Es como si prestaras tu cuaderno original: si alguien lo raya, tu cuaderno queda rayado.

imagen 3

<img width="771" height="408" alt="image" src="https://github.com/user-attachments/assets/e0d3c495-6c38-4ba2-a4ea-a330f3d5a046" />

## Respuesta: 

imagen 4

<img width="812" height="128" alt="image" src="https://github.com/user-attachments/assets/40af1dd8-0ba7-47a6-9500-22c285c36763" />

### <p align="center">📌 1.  Arreglos: 

Un arreglo es una estructura de datos que permite almacenar varios elementos del mismo tipo en posiciones consecutivas de memoria [3].

## caracteristicas: 

🔹 Todos los elementos son del mismo tipo (ej. enteros, caracteres).

🔹Se accede a cada elemento mediante un índice (posición).

🔹El índice comienza en 0 en la mayoría de lenguajes (como C, Java, Python).

## ventajas: 

🔹Organización de datos homogéneos.

🔹Acceso rápido a cualquier elemento.

🔹Útiles para recorrer datos con ciclos (for, while).

## 1.  <p align="center">TIPOS DE ARREGLOS</p>

## 1. Arreglo Unidimensional: 

Es una sola lista de elementos en línea.

## Ejemplo: 

Aquí numeros es una lista de 5 enteros. Cada posición se accede con un índice (numeros[0] = 10, numeros[1] = 20, etc.).

imagen 5 

<img width="733" height="343" alt="image" src="https://github.com/user-attachments/assets/2d7639bf-0013-4a50-a995-d537e6e0dd70" />

## Respuesta: 

imagen 6 

<img width="761" height="255" alt="image" src="https://github.com/user-attachments/assets/8715174e-0461-4a78-ab31-e8e7ace5db01" />

## 2. Arreglo Bidimensional (matriz)

Es una tabla con filas y columnas.

## Ejemplo: 

Aquí matriz tiene 2 filas y 3 columnas. Se accede con dos índices: matriz[0][0] = 1, matriz[1][2] = 6.

imagen 7 

<img width="827" height="474" alt="image" src="https://github.com/user-attachments/assets/029312fc-c7d7-4d93-829a-809a5710fa03" />

## Respuesta: 

imagen 8 

<img width="828" height="177" alt="image" src="https://github.com/user-attachments/assets/86795f88-3e4e-4032-a050-3a63bae7232c" />

## 3. Arreglo Multidimensional (más de 2 dimensiones)

Se usan para representar datos más complejos, como cubos o tablas de más niveles [4]. 

## Ejemplo: 

Aquí cubo es un arreglo de 3 dimensiones (como un cubo de datos). Se accede con tres índices: cubo[1][1][0] = 7.

imagen 9

<img width="837" height="439" alt="image" src="https://github.com/user-attachments/assets/d18384f5-270a-4cd3-9939-bdcc62399b84" />

## Respuesta: 

imagen 10

<img width="795" height="275" alt="image" src="https://github.com/user-attachments/assets/852c69d6-d2c4-4447-a0f4-b65eb132abc2" />

## <p align="center">Principales dificultades en la aplicación 
de los contenidos. </p>

- Dificultad para entender la abstracción detrás de modularidad y funciones.

- Confusión entre paso por valor y paso por referencia.

- Problemas para visualizar cómo los arreglos se almacenan en memoria.

- Olvidar inicializar variables o arreglos antes de usarlos.

- Errores en índices de arreglos (ej. acceder fuera de rango).

- Uso incorrecto de punteros al trabajar con referencias.

- Dificultad para dividir un problema grande en módulos pequeños.

- Problemas al elegir qué datos deben pasarse por valor y cuáles por referencia.

  ## <p align="center"> Reflexión crítica de los aprendizajes de la unidad </p>

  En esta unidad comprendí la importancia de la modularidad para organizar programas y facilitar su mantenimiento. Aprendí a diferenciar el paso por valor y el paso por referencia, entendiendo cómo influyen en la modificación de datos. También reforcé el uso de arreglos, desde listas simples hasta estructuras más complejas, aunque reconocí que los multidimensionales requieren mayor práctica.

Las principales dificultades estuvieron en la abstracción de conceptos y en los errores de sintaxis, pero descubrí que la práctica constante y la documentación clara son claves para superarlas. En conclusión, esta unidad me ayudó a fortalecer mi pensamiento lógico y a valorar la importancia de escribir código modular y eficiente.

  ## <p align="center"> ■ Tareas entregadas </p>

### ✔️ APE

Construcción de funciones y procedimientos en un lenguaje de programación

https://drive.google.com/file/d/1fhPEfnX6eL7a3J2ivSFyFSv1Egk-HmxP/view?usp=sharing
https://drive.google.com/file/d/1pzNAtK3d_yKmbscVAnc28CgWIi4alvCg/view?usp=sharing
https://drive.google.com/file/d/1pzNAtK3d_yKmbscVAnc28CgWIi4alvCg/view?usp=sharing

### ✔️ AA

Curso virtual de Cisco Networking Academy (Nov 05, 2025 - Jan 05, 2026) 

https://drive.google.com/file/d/19YQ4yBFHu81xHLB9AwKhn7K1teVU0B8i/view?usp=sharing 

## <p align="center">📌 Conclusiones generales


La modularidad es fundamental para organizar programas en funciones independientes, lo que facilita la comprensión, el mantenimiento y la reutilización del código.

El paso de parámetros por valor y por referencia permite controlar cómo se transmiten y modifican los datos dentro de las funciones, siendo clave para diseñar soluciones eficientes.

Los arreglos son estructuras esenciales para manejar grandes volúmenes de datos homogéneos; su uso correcto requiere práctica, especialmente en el caso de los multidimensionales.

Las principales dificultades se relacionan con la abstracción de conceptos, errores de sintaxis y la organización del código, pero se superan con práctica constante, documentación clara y ejemplos progresivos.

En conjunto, los contenidos de la unidad fortalecen el pensamiento lógico y estructurado, preparando al estudiante para enfrentar problemas más complejos en programación.























 

































[inicio](index.md)
