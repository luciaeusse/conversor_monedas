# conversor_monedas
Desarrollar una aplicación que permita convertir diferentes monedas utilizando el lenguaje de programación Java.

<h1 align="center"> Challenge ONE Java Sprint 01: Crea tu propio conversor de moneda </h1>

 ## Descripción del Proyecto
En esta oportunidad, a los Devs solicitó crear un conversor de monedas y lo que se le quisiera agregar utilizando el lenguaje Java.

Este Challenge forma parte del proyecto ONE – Oracle Next Education con Alula Latam en la ruta de formación de Java Orientado a Objetos, con esta formación se dio el conocimiento para desarrollar este challenge por medio de una serie de sprints y un tablero de Trello para organizar el trabajo.

![Challenge Oracle Next Education + Alura Banner](https://raw.githubusercontent.com/EduardoUT/ConversorMoneda-ONE-Alura_Challenge/master/src/Imagenes/challengeImage.jpg)

## Demostración

https://user-images.githubusercontent.com/94869227/175227834-69106d20-da14-4f59-9919-f5901f27b59a.mp4

## Funcionamiento 
Al iniciar la aplicación se da la opción de elegir entre el conversor de divisas o el conversor de temperatura, en este caso se utilizará el conversor de moneda

 ![image](https://user-images.githubusercontent.com/94869227/175188690-e65e0a38-4fa9-4a98-8bb3-7919e2823427.png)

saldrá un menú donde se nos indica las opciones que hay que para hacer la conversión de la divisa elegida

![image](https://user-images.githubusercontent.com/94869227/175188940-497978f1-6838-47ec-b2a0-eeeb6aee6a50.png)

 Una vez elegida la divisa aparece un cuadro de diálogo en el cual se tiene que ingresar el monto a convertir y la opción elegida 

![image](https://user-images.githubusercontent.com/94869227/175193479-c2206550-4208-4d4d-9d8a-9243ee4cfab5.png)

 En caso de que se ingrese un valor que no sea válido o no se ingrese ningún valor, se mostrará un mensaje de error y preguntará si quiere iniciar de nuevo.

![image](https://user-images.githubusercontent.com/94869227/175193624-376fef80-340c-44a1-bc60-e6c9a4bfc548.png)  ![image](https://user-images.githubusercontent.com/94869227/175195260-e2e93f0a-d01c-4413-9eb2-f106452f5c02.png) ![image](https://user-images.githubusercontent.com/94869227/175195307-81903641-6241-43a6-b2a1-364909adc8f3.png)

En el caso de que no haya ningún error, se despliega un cuadro de diálogo con la conversión solicitada.

![image](https://user-images.githubusercontent.com/94869227/175195532-ab5cb385-4e40-41e4-a41b-beda7ad93016.png)

 Finalizando muestra un cuadro para elegir si se quiere iniciar de nuevo el programa o se quiere terminar.

![image](https://user-images.githubusercontent.com/94869227/175196145-e2fb526b-68f4-4211-a876-de8073197612.png)
 
En el caso de que se decida terminar el programa, se mostrará un mensaje al usuario donde se indique "Programa Terminado"

![image](https://user-images.githubusercontent.com/94869227/175196388-d2c0ae51-3783-456a-836f-6b3e83150928.png)

En caso de seguir en el programa, se vuelve al comienzo para elegir otra conversión, en este caso el conversor de temperatura

### <h2> ¿Qué se utilizó? </h2>

Se utilizó java.io las operaciones de entrada/salida de Api 
Se Conectó la aplicación con una API de tipos de cambio en tiempo real, ya que las tasas cambian constantemente permitiendo que la aplicación siga funcionando de manera correcta independientemente del cambio en las tasas monetarias

![image](https://user-images.githubusercontent.com/94869227/175204627-89f42e4b-7d02-4ff2-81db-8553204c0936.png)

Se usaron validaciones para que a la hora de ingresar la información se pudiera recibir la respuesta correcta

se usaron Excepciones como NumberFormatException para poder evitar problemas de parte del Api, del programa o del usuario

se usó la librería javax.swing.JOptionPane para el manejo de interfaces gráficas, permitiendo mostrar el conocimiento adquirido en el lenguaje Java de una forma más accesible al usuario 

El código se agrupó en clases y en paquetes (package) para que su comprensión y mantenimiento fuera más fácil y entendible  




