# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Practica 1: Refexiones

## Identificación de la Actividad
- **ID de la Actividad:** P1.1
- **Módulo:**  EDES
- **Unidad de Trabajo:** 1º DAW A
- **Fecha de Creación:**   15/10/2024
- **Fecha de Entrega:** [Fecha de entrega]
- **Alumno(s):** 
  - **Nombre y Apellidos:** Cesar Gabriel Ucha Sousa
  - **Correo electrónico:** cuchsou815@g.educaand.es
  - **Iniciales del Alumno/Grupo:** CGUS

## Descripción de la Actividad
en esta actividad se responderan a una serie de preguntas con dl objetivo de reflexionar sobre lo aprendido hasta hoy en entornos de desarrollo

#### Relación software y hardware
1. ¿Cómo se ejecuta el código en el procesador?
Cada vez que ejecutamos el programa, este se carga en la memoria RAM, y la CPU va recuperando una a una las instrucciones y ésta las va ejecutando, llevando a cabo las tareas que el software tenía programadas.

2. ¿Qué hace la memoria RAM con la información del botón o el LED?
Almacena de forma temporal el código binario de los archivos ejecutables y los archivos de datos necesarios.

3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?
Se realizan mediante los buses de datos

4. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?
El procesador lee las instrucciones de la memoria RAM y estas se ejecutan en el botón y en la LED

5. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?
Que los datos se cargan en la memoria RAM

6. ¿Qué roles juegan las instrucciones del software en esta interacción?
Las instrucciones del software gian al procesador para manipular los datos de nuestro código y dicha manipulación responde con la interacción del botón y la LED

7.  ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?
la relación entre la simulación y un ordenador real está en que cuando pulsas el botón se inicia el programa guardando la información del botón en la memoria RAM esta envía unas instrucciones a la CPU y en función del programa que hayas utilizado se encenderá la LED y posteriormente se enviará la información a la memoria RAM

#### Del código fuente al ejecutable
1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?
El código fuente es el conjunto de instrucciones que el programador escribe utilizando un lenguaje de programación el código objeto es una versión compilada del código fuente y el código ejecutable es la versión final del programa que un ordenador ya puede ejecutar

2. ¿Por qué el ordenador no puede entender el código fuente directamente?
Porque solo entienden el lenguaje máquina

3. ¿Por qué es importante el paso de enlazado en la creación de programas?
Para enlazar las diferentes partes del código objeto junto con la librerías necesarias para que el código ejecutable funcione correctamente

4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?
Que el programa no funcionará

#### Generación de código intermedio
1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?
El código objeto está diseñado para convertirse en código ejecutable mientras que el código intermedio está diseñado para ejecutarse en una máquina virtual

2. ¿Por qué es útil tener una máquina virtual?
Porque se encargan de ejecutar el código intermedio, traduciendo este código a instrucciones que el procesador pueda entender

3. ¿Qué ventajas ofrece el código intermedio?
Portabilidad: El mismo programa puede correr en diferentes sistemas operativos sin necesidad de recompilar el código. Solo necesitas una máquina virtual para cada plataforma.
Seguridad: Las máquinas virtuales, como la JVM, pueden agregar capas de seguridad, ya que verifican y controlan el acceso del código intermedio al sistema operativo y al hardware. Esto evita que programas maliciosos accedan a áreas no autorizadas del sistema.
Optimización en Tiempo de Ejecución: Algunas máquinas virtuales utilizan técnicas como compilación Just-In-Time (JIT), que convierte el código intermedio en código de máquina justo antes de que sea ejecutado, optimizando el rendimiento del programa.

4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?
C#

#### Lenguajes de programación
1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?


2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?


3. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?


4. ¿Qué ventajas y desventajas encontraron en cada uno?


5. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?


6. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?


7. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?


8. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?


9. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?


10. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?


#### Herramientas de desarrollo
1. ¿Qué hace cada una de las herramientas?


2. ¿Qué tipo de tareas facilita?


3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?


4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?


5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?


6. Elige una ¿Qué limitaciones encontraste en la herramienta?


7. ¿Qué herramienta se considera más útil y por qué?


8. ¿Qué ventajas tiene una sobre la otra?


9. ¿Cuál herramienta resultó ser la más intuitiva y por qué?


10. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?


11. ¿Qué tipo de proyectos se benefician más de un framework que de Django?


12. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?


13. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?


14. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?


## Referencias y Fuentes
he buscado en las siguientes páginas web:
[revilofe.io](https://revilofe.io)
[tinkercad](https://www.tinkercad.com/things/b82nWvRGK9Z/editel)


