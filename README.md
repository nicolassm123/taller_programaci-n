nicolas macias gallego 


1.	En java los datos primitivos se dividen en ocho categorías 

Numéricos enteros. 

-Byte: es un entero de 8 bits con signo de rango -128 a 127
-Short: un entero de 16 bits con signo de rango -32,768 a 32,767
-Int: entero de 32 bits con signo de rango de -2,147,483,648 a 2,147,483,647
-Long: entero de 64 bits con signo de rango de -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807

Numéricos de punto flotante 

-Float: número de punto flotante de 32 bits de precisión hasta de 7 dígitos decimales.
-Double: número de punto flotante de 64 bits de precisión hasta de 15 dígitos decimales 

Otros tipos primitivos 

-Char: representa un solo carácter en unicocode de 16 bits y un rango ‘\u0000' 
a '\uffff

Boolean:  es de un 1 bit y representa valores de verdad solo pueden ser (true o false)


2.	Las estructuras de control de flujo en java se dividen en condicionales y bucles permitiendo tomar decisiones y repetir acciones.

-if, else: evalúan si una condición es verdadera ejecutara el bloque del código, si es falsa se ejecutará otro.

-if, else if, else: permiten evaluar varias condiciones en secuencia y se ejecuta el primer bloque que cumpla con la condición.

-switch: se utiliza cuando hay varios valores posibles para una sola variable.


Bucles 
-for: se utiliza cuando se conoce el número de repeticiones.
-while: ejecuta el bloque mientras la condición sea verdadera y es útil dado a que no se conoce cuantas se repite el proceso.
- do-while: garantiza que el bloque se ejecute al menos una vez antes de evaluar la condición.

3.	Al utilizar nombres significativos para las variables y proyectos en java es fundamental porque nos ayuda a mejorar la legibilidad y la compresión algunas de las razones son 
-facilita la lectura del código 
-reduce errores y confusión 
-aumenta la eficiencia en el desarrollo 
- buenas prácticas y estándares de calidad


4.	La programación orientada a objetos es un paradigma que organiza el código en objetos, los cuales representan entidades del mundo real con atributos como datos y métodos que son acciones.

5.	Los cuatro pilares de la programación orientada a objetos 

-Encapsulamiento: protege los datos que se encuentran dentro de un objeto, y dando acceso solo con métodos específicos.

-Herencia: permite que una clase obtenga atributos de y métodos de otra clase esto facilitando la reutilización del código y la organización.

-Polimorfismo: permite que una misma función o método tenga comportamientos diferentes según el contexto en el que se encuentre 

-Abstracción: oculta los detalles de un objeto y solo muestra su funcionalidad 





6.	La herencia es el mecanismo que permite que una clase llamada clase hija adquiera los atributos y métodos de otra clase que se llame clase padre esto facilita la reutilización de código, evita la duplicación y permite extender funcionalidades sin modificar la base.

7.	Los modificadores de acceso en java definen la visibilidad y el alcance de clases, atributos y métodos dentro del programa, los modificadores mas comunes en java son:

-prívate
-default
-protected
-public


8.	 Una variable de entorno es un valor almacenado en el sistema operativo que afecta la ejecución de progresos y programas, estas variables tienden a tener información importante como rutas de directorio, configuración del sistemas y credenciales. Son importantes porque facilita los siguientes ámbitos:

-configuración del entorno de desarrollo: variables como (java_home y path) aseguran que el jdk y herramientas como el javac sean reconocidas por el sistema

-facilitan la portabilidad: permite definir valores sin necesidad de modificar el código lo que hace es que las aplicaciones sean más adaptables en diferentes entornos.

-seguridad: almacena credenciales y claves API de forma segura evitando incluirlas directamente en el código 

-personalización del comportamiento de las aplicaciones: permite que una misma aplicación funcione en desarrollo, pruebas o producción cambiando solo las variables de entorno 




