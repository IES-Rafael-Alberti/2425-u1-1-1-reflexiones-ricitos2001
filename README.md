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
En un lenguaje compilado, la máquina de destino traduce directamente el programa. En un lenguaje interpretado, el código fuente se ejecuta linea por linea.

2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?
En el lenguaje compilado si hay un error el programa no compila por lo que no funciona, en el lenguaje interpretado se obtienen los errores en tiempo de ejecución

3. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?
Los lenguajes de alto nivel son más fáciles de entender, más abstractos y ofrecen muchas funcionalidades, en cambio los lenguajes de bajo nivel tiene más control y es más efectivo pero son difíciles de entender

4. ¿Qué ventajas y desventajas encontraron en cada uno?
Ventajas del lenguaje de alto nivel: 
* facilidad de aprendizaje
* productividad
* portabilidad
* abstracción
* comunidad y soporte
Desventajas de un lenguaje de alto nivel:
* Menos control sobre el hardware.
* Posible ineficiencia en la ejecución.
* Requiere compiladores o intérpretes.
* El tiempo de configuración aumenta porque se requieren diferentes traducciones del programa fuente para obtener el programa final.
* Los recursos internos de la máquina no se utilizan y se utilizan mejor en lenguaje máquina y ensamblador.
* Mayor huella de memoria.
* El tiempo de ejecución del programa es mayor.
Ventajas de un lenguaje de bajo nivel:
* Control directo sobre el hardware.
* Eficiencia en la ejecución del código.
* Menor abstracción, permitiendo optimizaciones específicas.
* Consumo reducido de recursos.
* Menor dependencia de bibliotecas externas.
* Capacidad para escribir sistemas operativos y drivers.
* Permite manipular directamente la memoria del ordenador.
* Ofrece una mayor velocidad y eficiencia en la ejecución.
* Facilita la creación de software avanzado con control y eficiencia.
Desventajas de un  lenguaje de bajo nivel: 
* dificultad de aprendizaje 
* dificultad de uso, y 
* mayor habilidad para el manejo de errores y
* mayor habilidad para el manejo de problemas de seguridad.

5. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?
El lenguajes organiza el código en objetos, que son instancias de clases. Los objetos encapsulan datos y comportamientos. Es útil cuando se desea modelar elementos del mundo real dentro del software.

6. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?
La programación con funciones puras quiere evitar cambios de estado tanto como sea posible y trabaja con flujos de datos entre funciones. En Python podría combinar los dos enfoques para escribir funciones que reciban y retornen instancias que representen objetos en su aplicación.

7. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?
Python ya que me parece mucho más sencillo y más fácil de entender

8. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?
En casos en los que el rendimiento, la eficiencia y la seguridad son más importantes que la flexibilidad y la portabilidad.

9. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?
Cuando la claridad, la rapidez y la facilidad de desarrollo son prioritarias para hacer un proyecto.

10. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?
Como hacer las cosas de una manera más ordenada

#### Herramientas de desarrollo
1. ¿Qué hace cada una de las herramientas?
GDB (GNU Debugger): Un depurador potente para lenguajes como C y C++. Permite ejecutar el programa línea por línea, inspeccionar variables y modificar su valor en tiempo real.
PDB (Python Debugger): Un depurador integrado en Python que permite ejecutar el código paso a paso, establecer puntos de interrupción y explorar el estado del programa.

2. ¿Qué tipo de tareas facilita?
Facilitan la depuración del código.

3. ¿Qué características ofrece que la hacen única o diferente de otras herramientas similares?
El depurador python (PDB) te permite inspeccionar tu código de forma interactiva, ver el código fuente, ir hacia arriba y hacia abajo del punto donde se ha producido un error, inspeccionar valores de variables, modificar valores de variables y establecer puntos de ruptura.
El depurador de GNU (GDB) ofrece puntos de ruptura, inspección de variables, ejecución paso a paso, depuración inversa, puntos de interrupción condicionales y scripting

4. Elige una ¿Cómo es la experiencia de usuario al usarla? ¿Es fácil o compleja?
es una buena experiencia ya que el depurador de python (PDB) es un programa que ayuda a identificar errores y facil de usar

5. Elige una ¿En qué situaciones sería ideal utilizar esta herramienta?
es ideal utilizar el depurador de python si el codigo tiene errores intermitentes, un comportamiento inesperado, códigos grandes o complejos, y el desarrollo de nuevas Funcionalidades

6. Elige una ¿Qué limitaciones encontraste en la herramienta?
el depurador de python (PDB) tiene limitaciones en cuanto interfaz de línea de comandos, rendimiento, funcionalidad limitada, depuración remota y complejidad en scripts grandes

7. ¿Qué herramienta se considera más útil y por qué?
El PDB (python debugger) ya que nos permite analizar el código línea por línea para detectar errores en nuestro código Fuente

8. ¿Qué ventajas tiene una sobre la otra?
El depurador de python tiene las siguientes ventajas:
Identificación de errores: La depuración te permite encontrar y corregir errores en tu código de manera eficiente. Esto significa menos tiempo perdido buscando problemas y más tiempo dedicado a desarrollar nuevas características.
Comprender el flujo de tu código: Al detener la ejecución en puntos específicos, puedes observar cómo se ejecuta tu código paso a paso. Esto es invaluable para comprender el flujo de tu programa y detectar posibles problemas de lógica.
Optimización del rendimiento: La depuración también se puede utilizar para analizar el rendimiento de tu código. Puedes identificar partes del programa que consumen demasiados recursos y realizar mejoras.

9. ¿Cuál herramienta resultó ser la más intuitiva y por qué?
el depurador de python PDB ya que te ayuda a detectar errores en tiempo real

10. ¿En qué casos se recomendaría usar un compilador en lugar de un intérprete?
En casos en los que valora la velocidad, la eficiencia, la portabilidad y la seguridad por encima del tiempo de desarrollo, la flexibilidad y las características dinámicas.

11. ¿Qué tipo de proyectos se benefician más de un framework que de Django?
Los proyectos para el desarrollo de aplicaciones web

12. ¿Cómo crees que impacta la elección de la herramienta en la calidad del software?
Desde la planificación inicial hasta la implementación y mantenimiento, exploraremos cómo los estándares de calidad no solo garantizan la funcionalidad y eficiencia del software, sino también su seguridad, usabilidad y adaptabilidad a las necesidades del usuario final.

13. ¿Qué características buscarías en una herramienta para facilitar tu flujo de trabajo?
buscaria la qutomatización de tareas, facilidad de uso e implementación, integración con otras herramientas y software, accesibilidad en múltiples plataformas y dispositivos, capacidades de colaboración y comunicación en tiempo real, administración de proyectos y tareas, funciones de seguimiento y medición de resultados, análisis de datos y generación de informes.

14. ¿Cómo cambió tu percepción de estas herramientas después de haberlas probado y evaluado?
antes pensaba que las herramientas de desarrollo de software no servian para nada pero ahora se que me equivocava y que las herramientas de desarrollo de software ayudan bastante

## Referencias y Fuentes
he buscado en las siguientes páginas web:
[revilofe.io](https://revilofe.io)
[tinkercad](https://www.tinkercad.com/things/b82nWvRGK9Z/editel)


