# Assignment2-BA
create database mysql;
use mysql;
create table airbnb_listings(
id int,
city varchar(50),
country varchar(50),
number_of_rooms int,
year_listed varchar(50)
)
select * from airbnb_listings;
Insert into airbnb_listings(id,city,country,number_of_rooms,year_listed) values(1,'karachi','pakistan',3,'2025'),
