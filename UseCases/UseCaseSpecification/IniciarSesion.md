# Caso de Uso: Iniciar Sesión

## 1. Descripcion Breve:
Cuando un Usuario quiere acceder al sector no publico del sitio web, debe identificarse mediante un usuario y una contraseña.

## 2. Actores
### 2.1 Actor Primario:
Usuario
### 2.2 Actor Secundario:


## 3.Curso básico:
3.1 - El caso de uso comienza cuando un usuario quiere acceder a su sector personal del sitio web.
3.2 - El sistema ofrece ingresar el nombre de usuario y contraseña o registrarse [extPoint Registrar]
3.3 - El usuario provee su nombre de usuario y contraseña.
3.4 - El sistema valida los datos
3.5 - El sistema permite el acceso
3.5 - Finaliza del caso de uso
En caso que los datos no coincidan el sistema informa del error y redirige al usuario a la pantalla de ingreso nuevamente.

## 4.Curso Alternativo

### 4.1 Validación incorrecta
#### 4.1.1 Usuario inexistente
3.4 - El sistema valida los datos
3.4.1.1 - El nombre de usuario proporcionado no existe.
3.4.1.2 - El sistema informa un error en los datos ingresados
3.4.1.3 - Ir al paso 3.2
#### 4.1.2 Contraseña incorrecta
3.4 - El sistema valida los datos
3.4.2.1 - La contraseña proporcionada no corresponde al usuario proporcionado.
2.4.2.2 - El sistema informa un error en los datos ingresados
2.4.2.3 - Ir al paso 3.2

## 5. Disparador:
El caso de uso comienza cuando un usuario quiere acceder a su sector personal del sitio web


## 6.Precondiciones:

### 6.1 Secretaria Registrada
La secretaria ya esta cargada en el sistema y no necesita registrarse.

## 7. Postcondiciones:

### 7.1 Login exitoso
El sistema concede acceso al sector personal del usuario del sitio web

## 8. Suposiciones:
## 9. Casos de uso Incluidos:

## 10. Casos de uso Extension:

#### 10.1 Registrar
El usuario completa el caso de uso Registrar y continua con el flujo básico en el punto 3.3

## 11.Finalizacion de caso de uso:
El sistema permite el acceso
