# PROYECTO INTEGRADOR - GRUPO PCADD - ABRIL

## *MARTES, 4 DE ABRIL*

Realizamos el inventario de los equipos disponibles del laboratorio
## *MIÉRCOLES, 5 DE ABRIL*

Reseteamos el router TP-Link y aprendimos a configurarlo para el proyecto

## *MARTES, 18 DE ABRIL*

- Elegimos el sistema operativo de cada servidor, y cómo vamos a agrupar los servidores virtualizados en los servidores físicos.
- Decidimos cómo vamos a organizar los equipos en el rack.
- Comprobamos si los equipos tenían internet

## *JUEVES, 20 DE ABRIL*

Hemos empezado a configurar el router TP-Link para configurar la red. Para ello hemos utilizado el programa Winbox:
  - Configuración de las interfaces y direcciones IP
  - Configuración sNAT para enmascarar
  - Configuración de ruta estática por defecto.

No hemos conseguido que funcione, no accede a Internet ni hace ping a la puerta de enlace

## *MIÉRCOLES, 26 DE ABRIL*

Continuamos configurando el router TP-Link.
Hemos encontrado dos errores en la configuración SOURCENAT:
  - El primero era que no seleccionamos la opción de sourcenat , nosotros lo pusimos a mano y en mayúscula.
  - El segundo error fue que en la máscara no pusimos la /24.
  Por último hemos conseguido que funcione el Microtik.
  
  ## *JUEVES, 27 DE ABRIL*
  
  En el dia de hoy nos hemos quedado en clase pensando y estructurando el esquema de red, al principio no teniamos
  mucha idea de como comenzar, pero entre todos hemos ido construyendo el esquema hasta que finalmente tenemos clara
  la distribución que usaremos en un futuro.

