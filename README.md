# Host info

Repositorio principal que encapsula los proyectos que componen el sistema Host info, sistema que permite consultar información relevante sobre host web.


## Repositorios forkeados
Este proyecto utiliza los repositorios [ssllabs](https://github.com/keltia/ssllabs) y 
[goscraper](https://github.com/badoux/goscraper)
de los autores `keltia` y `badoux` respectivamente, se han echo
modificaciones minimas a las librerias, arreglandolas en algunos casos
y obteniendo funcionalidades adicionales en otros.
## Ejecutando en local
### Backend
Como ejecutar: `go run main.go router.go servicecontainer.go`

Como iniciar las tablas de la base de datos:  `go run cli.go servicecontainer.go migrate`

Como borrar las tablas de la base de datos: `go run cli.go servicecontainer.go drop-tables`

### Frontend
Como instalar dependencias: `npm install`  

Como ejecutar: `npm run serve`


