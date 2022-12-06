# my-sql-hello-world

docker pull mysql
$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag
sudo docker exec -it my-sql bash
mysql -uroot -p
CREATE DATABASE helloworld
use helloworld

CREATE TABLE Persons (
    ->     PersonID int,
    ->     LastName varchar(255),
    ->     FirstName varchar(255),
    ->     Address varchar(255),
    ->     City varchar(255)
    -> );
    
INSERT INTO Persons (PersonID, LastName, FirstName, Address, City) VALUES (1,'shetty','shrihari','2044 N Beverly Plaza', 'Long Beach');

select * from Persons;
+----------+----------+-----------+----------------------+------------+
| PersonID | LastName | FirstName | Address              | City       |
+----------+----------+-----------+----------------------+------------+
|        1 | shetty   | shrihari  | 2044 N Beverly Plaza | Long Beach |
+----------+----------+-----------+----------------------+------------+
1 row in set (0.00 sec)
