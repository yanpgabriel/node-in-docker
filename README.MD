![Logo NodeJs + Docker](https://miro.medium.com/max/646/1*epfvG4ZmlzhhNCBPvFgC9A.png)
# Ambiente Docker com NodeJs
### Problema: Ambiente de desenvolvimento NodeJS customizavel e prático.
### Solução: Uso do Docker junto ao Docker-Compose para orquestração.  

---

Para começar coloque os arquivos **.dockerignore**, **docker-compose.yml** e **Dockerfile** no diretorio do projeto.  
Caso precise configurar algo como **PORTA** ou **COMANDO INICIAL** *(Ex: npm start)*, vá até o arquivo ***docker-compose.yml*** e altere!  

---

Para subir o ambiente use:
> docker-compose up -d  

Esse comando irá subir um *stack* no docker para um trabalho temporario ou permanente.  

---

Para remover ambiente use:
> docker-compose down  

Esse comando apaga todo **este** ambiente criado do docker como se não tivesse sido criado.  
***Obs: A pasta do projeto contendo os aruivos não seram apagados da maquina!***  
  
  ---  


Nesse projeto vem um "Hello World!" em [express](https://expressjs.com/pt-br/starter/hello-world.html) e [nodemon](https://nodemon.io/) para o live reload.

===

Necessidade: [Lucas](https://github.com/lcaresia)