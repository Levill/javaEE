MariaDB [javaee]> create table Usuarios(
    -> usuario_id int(10) primary key not null auto_increment,
    -> nombre varchar(25),
    -> apepat varchar(25),
    -> apemat varchar(25),
    -> ciudad_id int(10),
    -> estado varchar(25));
Query OK, 0 rows affected (0.16 sec)

MariaDB [javaee]> create table Ciudades(
    -> ciudad_id int(10) primary key not null auto_increment,
    -> nombre varchar(25),
    -> estado varchar(25));
Query OK, 0 rows affected (0.02 sec)

MariaDB [javaee]>

MariaDB [javaee]> insert into Ciudades(nombre,estado) values('Punta Arenas','act
ivo');
Query OK, 1 row affected (0.04 sec)

MariaDB [javaee]> insert into Ciudades(nombre,estado) values('Santiago','activo'
);
Query OK, 1 row affected (0.00 sec)

MariaDB [javaee]> insert into Usuarios(nombre,apepat,apemat,ciudad_id,estado) va
lues ('Juan','Perez','Perez',1,'activo');
Query OK, 1 row affected (0.01 sec)

MariaDB [javaee]> insert into Usuarios(nombre,apepat,apemat,ciudad_id,estado) va
lues ('Juan','Rojas','Perez',2,'activo');
Query OK, 1 row affected (0.00 sec)



