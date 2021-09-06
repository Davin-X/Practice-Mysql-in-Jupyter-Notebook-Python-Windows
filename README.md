# Practice-MySQL-in-Jupyter-Notebook-Python-Windows
 running and practicing MySQL in windows with python In Jupyter Notebook


In this we will be doing following tasks -> 

1- Installing MySQL-server in Windows (MySQL Sever 8, MySQL workbench 8)
2- installing MySQL connector for python
3- running and Practicing MySQL in Jupyter Notebook

Prerequisites => 
 Anaconda Individual Edition having - 
	-  python 3
	- Jupyter Lab / notebook

# 1- installing MySQL-server in Windows 

https://cdn.mysql.com//Downloads/MySQLInstaller/mysql-installer-web-community-8.0.26.0.msi
install and setup password 

 # 2 - installing MySQL connector for python
 Open anaconda prompt and run- 
	conda install -c anaconda mysql-connector-python

# 3 - running and Practicing MySQL in Jupyter Notebook
Run Jupyter notebook and create a new python notebook
Run- 
import mysql.connector

mydb = mysql.connector.connect(
  host="localhost",
  user="root",
  passwd="Mysql@password1"
)

print(mydb)

output-> <mysql.connector.connection.MySQLConnection object at 0x0000015DD39BEAC8>


now MySQL is up and running with python 
