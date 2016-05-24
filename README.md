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
