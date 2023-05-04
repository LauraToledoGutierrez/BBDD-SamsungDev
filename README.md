# BBDD-SamsungDev

Lo que se nos pide es algo sencillo, crear una tabla **USUARIO** con los siguientes campos: **ID, NOMBRE, APELLIDO, EMAIL**.

  - El campo **ID** será la *Primary Key*, autoincrementado.

  - Los campos **NOMBRE, APELLIDO, EMAIL** serán *Varchar(20)*.

Para crear la tabla con los campos se ha utilizado la siguiente consulta: 

CREATE TABLE USUARIO (  
    ID INT NOT NULL AUTO_INCREMENT,  
    NOMBRE VARCHAR(20) NOT NULL,  
    APELLIDO VARCHAR(20) NOT NULL,  
    EMAIL VARCHAR(20) NOT NULL,  
    PRIMARY KEY (ID)  
);

y para añadir valor a esos campos, la siguiente consulta:   
INSERT INTO USUARIO (NOMBRE, APELLIDO, EMAIL)   
VALUES ('Laura', 'Toledo', 'lauratoledogutierrez@gmail.com'),     
('Celia', 'Díaz', 'celia_diaz00@gmail.com'),     
('Pedro', 'Serrano', 'pedro.serrano99@gmail.com'),     
('Blanca', 'Pérez', 'blancaperezserrano@hotmail.com');    
