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

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/558564c5-6e28-45c2-9619-b36de9815d5d)

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/12e55fa2-911f-4597-8972-02d91ee25f64)

![image](https://github.com/ySodre/Docker_JavaWeb/assets/89286829/5d643a13-e11d-444f-a798-a21f78f18e90)

