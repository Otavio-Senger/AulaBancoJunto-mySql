# AulaBancoJunto-mySql

create database Tabelas;

use Tabelas;

create table serie_a(
id int primary key,
time1 varchar(20),
pontos int,
golspro int,
golscontra int,
saldodegols int
);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values (1, 'Flamengo', 50, 36, 12, 24);

select * from serie_a;

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(2, 'Palmeiras', 48, 37, 14, 23);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(3, 'Internacional', 44, 39, 26, 13);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(4, 'Vasco', 40, 23, 10, 13);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(5, 'Fluminense', 39, 25, 9, 16);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(6, 'Corinthians', 35, 30, 18, 12);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(7, 'Juventude', 33, 15, 10, 5);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(8, 'Red Bull Bragantino', 30, 20, 10, 10);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
values(9, 'Fortaleza', 29, 19, 11, 8);

insert into serie_a(id, time1, pontos, golspro, golscontra, saldodegols)
value(10, 'Bahia', 28, 15, 5, 10);

select * from serie_a;

delete from serie_a where id=2;

update serie_a set pontos = 53 where id=1;
