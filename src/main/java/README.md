desenvolve unha aplicación mínima que insira, modifique e elimine datos dunha taboa .
o script de creacion da taboa para facer as probas pode ser este :

drop table if exists personas;
create table personas(
id numeric,
nombre varchar(32),
apellido varchar(32),
salario numeric,
primary key (id)
)
;
insert into personas values (1,'luis','perez',2000.4);
insert into personas values (2,'ana','suarez',2100.427);
insert into personas values (3,'pedro','aguiño',1500.6123254);