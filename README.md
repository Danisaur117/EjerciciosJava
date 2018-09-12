# EjerciciosJava
## Ejercicios para prácticar el 1º Módulo de introducción a Java.
### 1º Actividad.
Escriba un métodos estático que tome un año como parámetro y devuelva false si el año es bisiesto y true en caso contrario.
### 2º Actividad.
Escriba un método que imprima la representación de su parámetro entero en números romanos. Por ejemplo, si el parámetro es 1998, la salida debe ser MCMXCVIII
### 3º Actividad.
Leer 10 datos numéricos y mostrarlos en orden inverso
### 4º Actividad.
Realizar un programa que no pida un unidad en kb y nos haga la conversión a MB
### 5º Actividad.
Realizar un programa que nos pida el radio y la altura y nos calcule el volumen de un cono.
### 6º Actividad.
Escriba un programa que calcule el tiempo de caída de un objeto determinado desde una altura dada, para ello se pide la altura en metros.
### 7º Actividad.
Escriba un programa que calcule la media de N numéro enteros introducidos.
### 8º Actividad.
Cree un programa que a partir de un entero calcule su serie Fibonacci
### 9º Actividad.
Cree un programa que calcule la potencia de un número a partir de su base y su exponente.
### 10º Actividad.
Cree un programa que dibuje en pantalla una pirámide a partir de una altura y un símbolo que se pedira al usuario.
### 11º Actividad.
Cree un programa que a partir de n números introducidos nos índique el número de números positivos introducidos y el número de números negativos introducidos.
### 12º Actividad.
Cree un programa que invierta el número que se pide el usuario por ejemplo si el usuario introduce 4561 el programa debe devolver 1654
### 13º Actividad.
Escribe un programa que muestre tres apuestas de la quiniela en tres columnas para los 14 partidos y el pleno al quince (15 filas)
### 14º Actividad.
Escribe un programa que pida 20 números enteros. Estos números se deben introducir en un array de 4 filas por 5 columnas. El programa mostrará las sumas parciales de filas y
columnas igual que si de una hoja de cálculo se tratara. La suma total debe aparecer en la esquina inferior derecha.
***
## Ejercicios para prácticar el 2º Módulo de introducción a Java POO
### 1º Actividad
Crea un BinaryArry , este BinaryArray es la representación privada  de una matriz de variables booleanas. Por ejemplo la rerpsentación del BinaryArrya "FTTF" sería una matriz de longitud cuatro que almacenaria (false, true, true false) en los índices 0,1,2,3 de la matriz, respectivamente. La clase BinaryArray tiene la sisguiente funcionalidad.
* Un constructor de un único parámetro que contiene un objeto String. 
* Metodos accesorios get/set para acceder a una variable en un índice concreto o modificarla.
### 2º Actividad
Cree una clase Cuenta que almacena el saldu actual y proporciona los métodos getBalance para obtener el saldo y deposit para depositar fondos, withdrar para reitrar fondos y toString para devolver por pantalla el saldo actual, además de al menos un constructor. Escriba y pruebe la clase.
### 3º Actividad
Implemente una clase, Polynomial, para representar polinomios de una sola variable y escriba un programa de pruebas. La funcionliada de la clsase Polynomial es la siguiente:
* Proporciona la mentos tres constructores: un constructor de cero parámetros que hace que el polinomio sea cero, un constructor que crea una copia independiente separada de un polinomio existente y un constructor que crea un polinio basado en una especificación String. 
* Crea el metodo negate que devuelve el negado del polinomio que se proporciona como parámetro.
* Crea los métodos add, substrac y multiply que devuelven un nuevo poliniomio que es igual a la suma, diferencia o producto, respectivamente, de este polinonio y de otro polinimio, rhs. Ninguno de estos métodos modifican ninguno de los polinimios originales.
* equals y toString, el primero comprueba que el polinio pasado por parámetro es el creado y toString  haga la representación en forma de cadena de caracteres tenga el mejor formato posible.
* El polinonio está representado por dos campos, de tal manera que el primer campo  ***degree*** representa el grado: x^2+2x+1 es de grado 2, 3x+5 es de grado 1 y 4 es de cardo 0  y cero es automaciamente el grado 0 y el segundo campo ***coeff*** reprenemta los coeficientes (coeff[i] respresenta el coeficiones de x^i)
### 4º Actividad
Queremos construir una aplicación que permita almacenar la información relevante sobre empresas y sus empleados:
* La clase empresa tendrá como mínimo dos atributos: nombre de tipo String y anyodefundacion de tipo string.
* La clase empleado tendrá como mínimo cuatro atributos: nombre de tipo String, apellidos de tipo String, fechanacimiento de tipo String y fechaContrato de tipo String 
El programa mostrará un menu que tendrá las siguientes opciones:
1. Crear nueva empresa.
2. Añadir empleado a empresa existente.
3. Listado de empresas.
4. Informacion de una empresa en particular.
5. Crear empleado.
6. Listado de empleados.
7. Información de un empleado en particular.
8. Salir.
Se deberá implementar todo la funcionalidad en las clases para que la aplicación sea funciona.
