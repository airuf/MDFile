#Based command

开启服务

	service mysqld start		

登录

	mysql -uroot -p				

显示数据库

	show databases;			

使用xxx

	use xxxx				

显示表

	show tables;        		

创建数据库xxxx

	create database xxxx;		


创建表xxxx

    create table xxx			
    {
    col_name  data_type(data_length),
    col_name  data_type(data_length),
    col_name  data_type(data_length)
    }
    eg.
    CREATE TABLE employee (id int(10),name char(20),phone int(12));


插入数据

    insert into table_name(col_nameA, col_nameB, col_nameC) values(value1, value2, value3);

    eg.
    INSERT INTO employee(id,name,phone) VALUES(01,'Tom',110110110);
    
    INSERT INTO employee VALUES(02,'Jack',119119119);
    
    INSERT INTO employee(id,name) VALUES(03,'Rose');


选择查看


	SELECT * FROM employee



加载数据

	source /home/dsaf/xxx.sql;

退出 

	quit 	
	exit					



1
#