Projeto - Java Simple Application
Disponível em: https://devopsrealtime.com/deploy-simple-java-application-using-docker-compose/
Repositório da aplicação: https://bitbucket.org/dptrealtime/java-login-app/src/master/

O objetivo desse projeto era subir uma aplicação web java, utilizando o tomcat, banco de dados mysql e o Nginx como proxy reverso.

1 - Utilizei o Apache Maven para criar o artefato .war no qual está a aplicação e as configurações de conexão com o banco
2 - Criei e configurei meu arquivo docker compose para criar uma stack com os três containers necessários para atender a demanda.
    - Nginx
    - Tomcat
    - Mysql
3 - No meu arquivo compose, criei uma rede bridge nova para apenas para o projeto e também utilizei volumes para persistir os dados do banco       de dados e realizar a constumização das configurações. 
