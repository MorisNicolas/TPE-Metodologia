# Caso de Uso: Generar Recorrido

***

## 1.Descripción Breve:
>El sistema automáticamente a una hora especifica en los días laborales, crea un listado con cada uno de los empleados indicando que domicilio tendrán que ir a buscar los materiales reciclables y a qué hora tienen que estar allá.

***
## 2. Actores
### 2.1 Actor Primario:
>Reloj.

***

## 2.2 Actor Secundario
>Secretaria
***

## 3.Curso básico:
>
>>3.1 El caso de uso comienza cuando son las 8am. de un día laboral
>
>>3.2 El sistema inicia el algoritmo para generar el listado, chequeando las siguientes restricciones:
• Se deberá ser equitativo con todos los cartoneros.
• No se deberá asignar de forma diaria a un cartonero más de lo que puede
transportar en su vehículo.
• El total del recorrido (incluido el viaje hasta el depósito) no debe superar los 6km.
• En aquellos casos donde el volumen a retirar corresponde a la categoría “a”, solo
se le deberá asignar a un cartonero en caso de que el lugar de recolección quede
en su camino a otras viviendas con categorías de volumen mayores (es decir, “b”, “c” y “d”)
>
>>3.3 El sistema envia el listado generado al correo de la secretaria.
>
>>3.4 El caso de uso finaliza.

***

# 4.Curso Alternativo
> En caso que no se puedan cumplir alguna restriccion, esta debe ser impresa al final del mail.
> El caso de uso finaliza.

***

## 5.Trigger:
>El caso de uso inicia en un día laboral a las 8am. creando el listado de recorrido.

## 6.Precondicion

***

## 7.Postcondición:

> El listado fue enviado a la secretaria.
***

## 8.Suposiciones:

***

## 9.Casos de Uso Includes:

***

## 10.Casos de Uso Extension

***

## 11.Finalizacion de caso de uso:
>Se envio el listado

***
