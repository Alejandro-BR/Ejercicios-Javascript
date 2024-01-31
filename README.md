# Ejercicios-Javascript

**Alejandro Barrionuevo Rosado**

**Lenguajes de marcas y sistemas de gestión de información**

**Ejercicios de Realización y entrega con Javascript**

1. Calcula el área y el perímetro de un rectángulo usando una clase Rectángulo
donde tenga la función calculaArea y la función calculaPerímetro y la función
resultadofinal. El formulario de entrada debe tener, como mínimo este aspecto:


2. Crear programa, donde el usuario introduce su altura (cm), edad, sexo y peso
actual. El programa responde con el peso ideal.

        Por ejemplo: usuario introduce 176, 22, H, 79.
        El programa ejecuta la fórmula: 50 + ((Altura-150) / 4) *3 + (Edad – 20) /4 * (0.9 si es mujer)
        El resultado es: peso ideal = 70,5.KG
        Los datos se introducirán mediante prompts, tal y como se muestran:


3. Crear programa, que realice la evaluación de la fórmula matemática expresada en
la casilla de recogida de datos y muestre su resultado en la casilla de Respuesta.
Tendrías que usar la función eval() que es propia de Javascript.


4. Crear programa, que leerá el valor desde una caja de texto de un formulario y tras
dar al botón de calcula nos ofrecerá la tabla de multiplicar de ese número
introducido previamente.


5. El cálculo de la letra del Documento Nacional de Identidad (DNI) es un proceso
matemático sencillo que se basa en obtener el resto de la división entera del número de DNI y el número 23. A partir del resto de la división, se obtiene la letra
seleccionándola dentro de un array de letras.

        El array de letras es:
        var letras = ['T', 'R', 'W', 'A', 'G', 'M', 'Y', 'F', 'P', 'D', 'X', 'B', 'N', 'J', 'Z', 'S', 'Q', 'V', 'H',
        'L', 'C', 'K', 'E', 'T'];

        Por tanto, si el resto de la división es 0, la letra del DNI es la T y si el resto es 3 la letra es la A.
        Con estos datos, elaborar un pequeño script que:

        • Almacene en una variable el número de DNI indicado por el usuario y en otra variable
        la letra del DNI que se ha indicado. (Pista: si se quiere pedir directamente al usuario que
        indique su número y su letra, se puede utilizar la función prompt())

        • En primer lugar (y en una sola instrucción) se debe comprobar si el número es menor
        que 0 o mayor que 99999999. Si ese es el caso, se muestra un mensaje al usuario indicando que el número proporcionado no es válido y el programa no muestra más mensajes. 

        • Si el número es válido, se calcula la letra que le corresponde según el método explicado
        anteriormente. 

        • Una vez calculada la letra, se debe comparar con la letra indicada por el usuario. Si no
        coinciden, se muestra un mensaje al usuario diciéndole que la letra que ha indicado no
        es correcta. En otro caso, se muestra un mensaje indicando que el número y la letra de
        DNI son correctos. 

