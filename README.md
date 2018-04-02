# Deitel-Java-Ejercicio-7.19
Como Programar en Java 10 Edicion Paul Deitel. Ejercicio 7.19 (Sistema de reservaciones de una aerolínea)

Una pequeña aerolínea acaba de comprar una computadora para su nuevo sistema de reservaciones automatizado. Se le ha pedido a usted que desarrolle el nuevo sistema. Usted escribirá una aplicación para asignar asientos en cada vuelo del único avión de la aerolínea (capacidad: 10 asientos).

Su aplicación debe mostrar las siguientes alternativas: Por favor escriba 1 para Primera Clase y Por favor escriba 2 para Economico. Si el usuario escribe 1, su aplicación debe asignarle un asiento en la sección de primera clase (asientos 1 a 5). Si el usuario escribe 2, su aplicación debe asignarle un asiento en la sección económica (asientos 6 a 10). Su aplicación deberá entonces imprimir un pase de abordar, indicando el número de asiento de la persona y si se encuentra en la sección de primera clase o clase económica.

Use un arreglo unidimensional del tipo primitivo boolean para representar la tabla de asientos del avión. Inicialice todos los elementos del arreglo con false para indicar que todos los asientos están vacíos. A medida que se asigne cada asiento, establezca el e lemento correspondiente del arreglo en true para indicar que ese asiento ya no está disponible.

Su aplicación nunca deberá asignar un asiento que ya haya sido asignado. Cuando esté llena la sección econó- mica, su programa deberá preguntar a la persona si acepta ser colocada en la sección de primera clase (y viceversa). Si la persona acepta, haga la asignación de asiento apropiada. Si no, imprima el mensaje “El proximo vuelo sale en 3 horas”.
