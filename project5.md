## Step1 

## Implement a Client Server Architecture using MySQL Database Management System

`sudo apt update -y`

![apt update](./images/sudo-update.PNG)

`sudo apt install mysql-server -y`

![Sql server install](./images/sqlserver-install.png)

`sudo apt install mysql-client -y`

![Sql server client](./images/sqlclient-install.png)

`sudo systemctl enable mysql`

![Sql server client](./images/sql-start.png)

`sudo sql`

![sudo Sql ](./images/sudo-sql.png)

`sudo mysql_secure_installation`

![secure Sql ](./images/secure-sql.png)

`create user & database`

![create user & DB ](./images/user&db-create.png)

`cat mysqld.cnf`

![view mysqld.cnf file ](./images/bind-add.png)

`tcp-3306`

![TCP-3306 rule ](./images/sql-rule.png)

`sudo systemctl enable mysql`

![start sql_server  ](./images/sql-start.png)

`sudo mysql -u remote_user -h 172.31.28.28 -p`

![remote login from client sql](./images/remote-login.png)


`Show databases`

![databse view from client login ](./images/show-db.png)


