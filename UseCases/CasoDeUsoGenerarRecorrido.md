# Nombre del caso de uso: 
>Generar Recorrido.

## 1.Descripción: 
>El sistema automáticamente a una hora especifica en los días laborales, crea un listado con cada uno de los empleados indicando que domicilio tendrán que ir a buscar los materiales reciclables y a qué hora tienen que estar allá.

## 2.Actor Primario: 
>Reloj.

## 3.Curso básico: 
>
>> El caso de uso comienza cuando son las 8am. de un día laboral
>
>> El sistema inicia el algoritmo para generar el listado.
>
>> El algoritmo crea el listado de recorrido.
>
>> Automáticamente al crear el listado, el listado es enviado al correo de la secretaria.
>
>> El sistema recibe la confirmación mediante la secretaria que el listado de recorrido llego correctamente.
>
>> El caso de uso finaliza.

## 4.Trigger: 
>El caso de uso inicia en un día laboral a las 8am. creando el listado de recorrido.

## 5.Postcondición: 
>
>> El sistema es notificado que la secretaria recibió el listado de recorrido.

## 6.Suposiciones: 
>
>> El email es el que está registrado en su cuenta.

## 7.Casos de uso incluidos: 
>
>>Acceder Recorrido.

## 8.Finalizacion de caso de uso: 
>
>> Se desarrollo correctamente.
>
>> La secretaria no confirma la llegada del listado. 
