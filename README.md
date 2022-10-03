# SQL basic SELECTS

SQL introduction for the unit 1.

### For series table creation.

CREATE TABLE series(
   Enviado VARCHAR(100) NOT NULL 
  ,DNI     VARCHAR(100) NOT NULL PRIMARY KEY
  ,Nombre    VARCHAR(100) NOT NULL
  ,Genero    VARCHAR(228) NOT NULL
);

### Insert ...

INSERT INTO `favorites`(`Timestamp`,`title`,`genres`) VALUES ("10/25/2021 11:21:46","How i met your mother","Comedy");


# Show all customers table columms.

SELECT * FROM Customers;
