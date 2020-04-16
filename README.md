# POS Backend

_Este es el backend del [Pos Angular](https://github.com/Franklingp/portafolioAngular) este al igual que en el cliente tiene esta subdividido en 3 subsistemas, cada uno tiene su base de datos y sus respoectivas rutas, al igual que para cada uno se permite guardar, actualizar, visualizar y eliminar sus datos, el objetivo es llevar un registro de los clientes, las ventas y el inventario de un negocio_

### Pre-requisitos 📋

_Para poder ejecutar este proyecto necesitas tener disponible en tu PC Node JS, MongoDB y npm para poder descargar las dependencias necesarias y poder ejecutar el proyecto en un servidor local_

### Instalación 🔧

_Para poder correr este proyecto necesitas clonar el repositorio e instalar las dependencias necesarias con npm usando el siguiente codigo dentro de la carpeta del proyecto._

```
npm install --save
```

_Y luego de que instale todas las dependencias necesarias debes correr habilitar mongoDB para que NodeJS pueda tarbajar con la base de datos, esto lo puedes hacer con el siguiente comando en caso de que tengas Linux:_

```
sudo service mongod start
```

Y ahora si puedes correr el proyecto con:

```
npm start
```

_De esta forma tendras el proyecto corriendo en un servidor local en tu computadora, por defecto el puerto que que he definido es 3700, asi que el proyecto debe de estar corriendo en la ruta http://localhost:3700/_

## Construido con 🛠️

_Este proyecto esta construido con Node JS, Express y Mongoose