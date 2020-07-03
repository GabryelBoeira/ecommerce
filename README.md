# Ecomerce
Serviço para cadastro de cliente, produto, e pedido com Spring 

# Tecnologias Utilizadas e Dependencias
:Spring Initializr: https://start.spring.io/
:Project: Mavem Repository  
:Spring Boot: 2.3.1.RELEASE
:Language: Java - JDK 8
:Dependencies: Spring Web, MySQL Driver, Spring Data JPA
:DataBase: Oracle - MySQL 

# Inicialização do Projeto no Sistema

Configuração do Banco de dados OBS: (Mysql já deve estar instalado)
====
[source, mysql]
----
mysql> create database ecommerce; -- Criar a database utilizada 
mysql> create user 'admin'@'%' identified by 'nimda'; -- Criar Usuario 
mysql> grant all on ecommerce.* to 'admin'@'%'; -- Permição máxima ao usuario para a database 
----
====