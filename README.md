# Parcial 2

## Pasos de isntalacion:

### Instalacion
ubicarse en la carpeta deseada y ejecutar "git clone https://github.com/YesidMG/Parcial2.git"

## Correr programa:
asegurese de estar dentro de la carpeta del repositorio clonado
aegurese que el puerto 8080 no esta en uso

ejecute el comando "docker compose up --build"

### Acceder a traefik
acceda mediante "localhost:8080"

### Acceder a clientes:
existen 2 clientes, 

Cliente 1: localhost/cliente/1
Cliente 2: localhost/cliente/2

esto mostrara el header con la info del cliente

### Reporte
para ver el reporte de las peticiones realizadas a los clientes se debe ingresar a "localhost/registro"

pedira una autenticacion la cual sera 
Usuario:yesid
contraseña:yesid

mostrara el registro de forma

{numeroCliente : Numero de peticiones}
ejemplo: {1:18 , 2:34}

### Panel
Para ver el panel se usa "localhost/panel"