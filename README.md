# INTRODUCCION A SQL

1. Creacion de una base de datos (BD) con MySQL phpMyAdmin

## Creacion tabla Cliente
### Diccionario de datos
|Campo|Tipo de dato|Longitud|
|-----|------------|--------|
|***identificacion**|varchar|15|
|nombre|varchar|20|
|apellidos|varchar|20|
|direccion|varchar|25|
|telefono|varchar|20|
|ciudad_nac|varchar|20|
|fecha_nac|data||

### Codigo SQL de creacion de tabla de cliente
CREATE TABLE `Ventas`.`Cliente` (`identificacion` VARCHAR(15) NOT NULL , `nombre` VARCHAR(20) NOT NULL , `apellidos` VARCHAR(20) NOT NULL , `direccion` VARCHAR(25) NOT NULL , `telefono` VARCHAR(20) NOT NULL , `ciudad_nac` VARCHAR(20) NOT NULL , `fecha_nac` DATE NOT NULL , PRIMARY KEY (`identificacion`)) ENGINE = InnoDB;

### Diccionarion de datos en phpMyAdmin
![Diccionario de datos](diccionario.png "Diccionario de datos")

### Registro de datos en tabla Cliente

### Codigo SQL de insercion de un registro a la tabla Cliente
INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('100', 'Juan David', 'Rodriguez Garcia', 'Cra. 26 #2-16', '313 3112418', 'San Gil', '2006-02-28');

INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('101', 'Kevin Daniel', 'Solano Cardenas', 'Cra. 20 #2-16', '319 7794793', 'Bogota', '2006-01-06');

INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('102', 'jose luis ', 'castro carrero', 'calle 13 #6-04', '3026659391', 'Bogota', '2006-01-30');

INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('103', 'Ivan David', 'Rodriguez Salamanca', 'Cra 15 # 16', '304 4235307', 'Bogota', '2006-04-01');

INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('104', 'David Santiago', 'Mayorga', 'calle 19 #6-23', '322 7451386', 'San Gil', '2006-12-05');

INSERT INTO `Cliente` (`identificacion`, `nombre`, `apellidos`, `dirrecion`, `telefono`, `ciudad_nac`, `fecha_nac`) VALUES ('105', 'Danny Fernei', 'Ardila Ardila', 'Calle 3 # 15-21', '316 5736850', 'San Gil', '2006-03-08');


### Primer registro phpMyAdmin
![Registro de datos](registros.npg "Registro de datos")