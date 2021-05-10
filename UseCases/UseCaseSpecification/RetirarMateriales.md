# Nombre del caso de uso: Retirar materiales

## 1.Descripción:
> El cartonero está listo para salir a retirar material reciclable a los domicilios de los ciudadanos.

## 2. Actores

### 2.1 Actor Primario: 
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
