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
>> El algoritmo busca los domicilios de los cuales los empleados deben visitar
>
>>El mismo algoritmo debe seleccionar domicilios para cada empleado que pueda buscar esos materiales cumpliendo correctamente con la categoria de transporte y sin superar la distancia maxima
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


# Nombre del caso de uso: 
> Retirar materiales

## 1.Descripción: 
> El cartonero está listo para salir a retirar material reciclable a los domicilios de los ciudadanos.

## 2.Actor Primario: 
> Cartonero

## 3.Curso básico: 
>
>> El caso de uso comienza luego de que el cartonero incia sesión
>
>> El cartonero recibe su recorrido diario
>
>> El cartonero visita un domicilio
>
>> Luego de visitar un domicilio se marca como visitado y se prosigue con el siguiente
>
>> Todos los domicilios fueron visitados
>
>> El caso de uso finaliza

## 4.Curso alternativo:
>
>> El caso de uso comienza luego de que el cartonero incia sesión
>
>> El cartonero recibe su recorrido diario
>
>> El cartonero visita un domicilio
>
>> El cartonero visita un domicilio en el que no hay nadie para recibirlo
>
>> El cartonero visita el siguiente domicilio en la lista
>
>> Todos los domicilios fueron visitados
>
>> El caso de uso finaliza

## 5.Trigger: 
> El caso de uso inicia luego del inicio de sesión del cartonero

## 6.Precondición
>
>> El cartonero finalizó el caso de uso "Iniciar sesión"

## 7.Suposiciones: 
>
>> El caso de uso "Generar recorrido" ya fue activado

## 8.Finalizacion de caso de uso: 
>
>> Todos los domicilios fueron visitados


# Nombre del caso de uso: 
> Finalizar recorrido

## 1.Descripción: 
> El cartonero está listo para regresar a la cooperativa

## 2.Actor Primario: 
> Cartonero

## 3.Curso básico: 
>
>> El cartonero ya no tiene domicilios en su lista
>
>> El cartonero marca como finalizado su recorrido

## 4.Curso alternativo:
>
>> El cartonero tiene domicilios en los que no había gente en su lista
>
>> El cartonero marca como finalizado su recorrido
>
>> El cartonero regresa a la cooperativa
>
>> El caso de uso finaliza

## 5.Trigger: 
> El caso de uso inicia luego de retirar los materiales

## 6.Precondición
>
>> El cartonero finalizó el caso de uso "Retirar materiales"

## 7.Suposiciones: 
>
>> El cartonero ya finalizó el caso de uso "Iniciar sesión"
>
>> El caso de uso "Generar recorrido" ya fue activado

## 8.Finalizacion de caso de uso: 
>
>> El cartonero regresa a la cooperativa


# Nombre del caso de uso: 
>Pesar Materiales

## 1.Descripcion Breve: 
>El cartonero quiere pesar los materiales recogidos de los domicilios.

## 2.1Actor Primario: 
>Cartonero.

## 2.2Actor Secundario: 
>Balanza.

## 3.Curso básico: 
>
>>El empleado llega al centro de acopio y quiere cargar en el sistema el peso de los materiales que trajo de los domicilios.
>
>>El empleado debe iniciar sesión en el sistema.
>
>>El empleado selecciona que material va a pesar en la balanza.
>
>>[INCLUDE] Cargar kilos a cartonero.
>
>>El empleado selecciona en el sistema que ya termino de cargar materiales.
>
>>El caso de uso finaliza.

## 4.Trigger: 
>El caso de uso inicia cuando el empleado llega al centro de acopio y quiere pesar los materiales recogidos.

## 5.Precondición: 
>
>>El empleado debe iniciar sesión correctamente en el sistema antes de pesar los materiales.

## 6.Casos de uso Incluidos: 
>
>>Cargar kilos a cartonero.

## 7.Finalizacion de caso de uso: 
>
>>El caso de uso se desarrolló de forma correcta.                 
