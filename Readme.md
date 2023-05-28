![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/8eb9e20d-27e2-4071-8460-4c76b34aecc4)

# Projeto - Java Simple Application
Disponível em: https://devopsrealtime.com/deploy-simple-java-application-using-docker-compose/

Repositório da aplicação: https://bitbucket.org/dptrealtime/java-login-app/src/master/

O objetivo desse projeto era subir uma aplicação web java, utilizando o tomcat, banco de dados mysql e o Nginx como proxy reverso.

1 - Utilizei o Apache Maven para criar o artefato .war no qual está a aplicação e as configurações de conexão com o banco

2 - Criei e configurei meu arquivo docker compose para criar uma stack com os três containers necessários para realizar a tarefa.

4 - Fiz mapeamentos de volumes para o mysql e o tomcat, com o objetivo de persistir os dados do banco de dados e ter acesso aos arquivos de configurações do Tomcat

5 - Criei uma rede nova com o drive bridge apenas para essa stack de containers

6 - Nesse projeto pude práticar as seguintes skills:

    * Docker Compose
    * Docker 
    * Volumes
    * Redes bridge
    * Proxy Reverso com Nginx
    
## Validação

### Após subir os containers com o docker compose: Tomcat, Mysql e Nginx foi possível acessar a aplicação via página web utilizando o endereço configurado no proxy nginx e em seguida fazer login com sucesso.

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/5d643a13-e11d-444f-a798-a21f78f18e90)

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/ff702ac2-c714-42e2-8cde-93ff37a7fc38)

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/d5d6680f-885d-4651-be71-030c237c2914)



