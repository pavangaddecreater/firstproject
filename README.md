create table customerdetails(
customer_id INT NOT NULL,
customer_name VARCHAR2(50),
customer_loc VARCHAR2(50),
customer_ph Number,
customer_id int primary key
);

insert into customerdetails values(1,'Likitha','Guntur',9882345671);
insert into customerdetails values(2,'Priyanka','Hyderabad',7623457890);
insert into customerdetails values(3,'Navya sri','Vijaywada',9012364578);
insert into customerdetails values(4,'akilesh','Nalgonda',8901234567);
insert into customerdetails values(5,'malik','WestGodavari',7612378934);
insert into customerdetails values(6,'sowmya','EastGodavari,9812786346);
insert into customerdetails values(7,'shravya','Nellore',8761289023);
insert into customerdetails values(8,'shiva','Chennai',9128374690);
insert into customerdetails values(9,'rakesh','Banglore',9127934087);
insert into customerdetails values(10,'sunada','Kurnool',8012683945);





CREATE TABLE Cart(
customer_id NUMBER,
customer_name VARCHAR2(50),
customer_loc VARCHAR2(20),
Product_ID NUMBER,
Amount INT NOT NULL
date_of_purchase VARCHAR2(20),
Product_ID int primary key
);

insert into Cart values(1,'Likitha','Guntur',1001,1200,'01/01/2016');
insert into Cart values(2,'Priyanka','Hyderabad',1004,2000,'02-02-2011');
insert into Cart values(3,'Navya sri','Vijaywada',1018,1100,'03-03-2012');
insert into Cart values(4,'akilesh','Nalgonda',1011,4000,'04-04-2013');
insert into Cart values(5,'malik','WestGodavari',1014,1999,'05-05-2014');
insert into Cart values(6,'sowmya','EastGodavari,1004,2000,'06-06-2015');
insert into Cart values(7,'shravya','Nellore',1011,4000,'07-07-2016');
insert into Cart values(8,'shiva','Chennai',1019,5600,'08-08-2017');
insert into Cart values(9,'rakesh','Banglore',1012,5899,'09-09-2018');
insert into Cart values(10,'sunada','Kurnool',1021,4500,'10-10-2019');






Create table Products(
Product_ID INT NOT NULL,
Product_Name VARCHAR2(50),
Amount INT NOT NULL,
Product_size VARCHAR2(50),
Product_ID int primary key
);

insert into Products values(1000,'Raymond',5000,'M');
insert into Products values(1001,'Uspolo',1200,'M',);
insert into Products values(1002,'Tommyhillfiger',7500,'M');
insert into Products values(1003,'Wrangler',3500,'M');
insert into Products values(1004,'Killer',2000,'M');
insert into Products values(1005,'Netplay',900,'M');
insert into Products values(1006,'Killer',5000,'L');
insert into Products values(1007,'Wrangler',1180,'XXL');
insert into Products values(1008,'Netplay',1200,'XL');
insert into Products values(1009,'Netplay',500,'M');
insert into Products values(1010,'Netplay',2000,'L');
insert into Products values(1011,'Killer',4000,'XL');
insert into Products values(1012,'Killer',5899,'XXL');
insert into Products values(1013,'Tommyhillfiger',4200,'L');
insert into Products values(1014,'Wrngler',1999,'XL');
insert into Products values(1015,'Wrangler',2000,'S');
insert into Products values(1016,'Uspolo',3499,'M');
insert into Products values(1017,'Uspolo',4000,'XL');
insert into Products values(1018,'Raymond',1100,'L');
insert into Products values(1019,'Raymond',5600,'S');
insert into Products values(1020,'Tommyhillfiger',1999,'XL');
insert into Products values(1021,'Uspolo',4500,'S');
insert into Products values(1022,'Tommyhillfiger',5500,'S');
insert into Products values(1023,'Raymond',2300,'XXL');
insert into Products values(1024,'Killer',3500,'XXXL');




create table Seller(
Seller_ID VARCHAR2(10) NOT NULL,
Product_ID INT NOT NULL,
Amount INT NOT NULL,
Seller_ID,Product_ID int primary key
);

insert into Seller values('S1',1000,5000);
insert into Seller values('S2',1001,1200);
insert into Seller values('S3',1002,7500);
insert into Seller values('S4',1003,3500);
insert into Seller values('S5',1004,2000);




create table Salesperson(
salesperson_ID INT NOT NULL,
customer_loc VARCHAR2(50),
customer_ph Number,
product_ID INT NOT NULL,
Amount INT NOT NULL,
date_of_delivery VARCHAR2(20),
salesperson_ID int primary key
);

insert into Salesperson values(100,'Guntur',9882345671,1000,5000,'12-8-2020');
insert into Salesperson values(101,'Hyderabad',7623457890,1001,1200,'10-10-2020');
insert into Salesperson values(102,'Vijaywada',9012364578,1002,7500'10-11-2020');
insert into Salesperson values(103,'Nalgonda',8901234567,1003,3500,'10-12-2020');
insert into Salesperson values(104,'WestGodavari',7612378934,1004,2000,'05-07-2019');
insert into Salesperson values(105,'EastGodavari,9812786346,1005,900,'09-10-2020');
insert into Salesperson values(106,'Nellore',8761289023,1006,5000,'08-09-2020);
insert into Salesperson values(107,'Chennai',9128374690,1007,1180,'07-10-2020);
insert into Salesperson values(108,'Banglore',9127934087,1008,1200,'06-09-2020);
insert into Salesperson values(109,'Kurnool',8012683945,1009,500,'05-10-2020);

