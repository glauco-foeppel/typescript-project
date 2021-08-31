### Estudo typescript
projeto criado com fins de aprendizado na linguagem typescript.

> **Node.js versao** = ```^15.12.2```
**Yarn versao** = ``` v1.22.10 ```
### instalação
- Clone o projeto para o pc
- No termial, rode o comando ```yarn install``` na raiz do diretorio
- Crie o container do postgres no docker seguindo instruções abaixo
- No terminal rode o comando ``` yarn dev ```
- A aploicação estará disponivel em ```localhost:3333```

### Banco de dados
Necessário ter o docker instalado e rodando no pc.
[docker](https://www.docker.com/)
```sh
docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```
O comando acima cria o banco de dados postgres no docker com o seguinte acesso:

``` sh
host: localhost
database: postgres
username: postgres
password: docker
```
