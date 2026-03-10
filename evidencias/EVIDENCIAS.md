# Evidencias
He configurado el repositorio para que sea necesario hacer un pull request antes del merge por parte del propietario. Es importante proteger la rama principal del proyecto para que asi evitemos subir codigo que parta el buen funcionamiento de este, y asi poder llevar un control sobre lo que se va subiendo.

## Gitignore
He agregado con * todos los archivos con extensión .log más el directorio __pycache__/. 

## Enlace 
https://github.com/JavierOrtegaAL/Entrega01.git

## Flujo de Trabjao
Primero trabaje con la rama master, despues cree una rama feature/gitignore para agregar los ficheros .gitignore. Despues cree dos ramas una feature/suma con una suma sencilla y otra feature/resta con una resta sencilla. Subi primero la rama feature/suma y luego hice un pull para traerme los cambios una vez mergeados, resolvi los conflictos con la rama feature/resta y lo subi con un push. Por ultimo cree la rama feature/ci para el fichero actions demo.yml. En todo momento he estado trabajando con pull request.

## Resolucion de conflictos
Al trabajar con pull request ha sido sencillo resolver los conflictos, ya que quitando la suma y resta en el resto de push no me han surgido.

## Workflow Actions
Pide un nombre y unos apellidos e imprime Me llamo seguido del nombre y los apellidos.