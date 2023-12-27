## Objetivo

Esta pasta contém o arquivo com a coleção do postman, com as requisições por caso de teste e os testes automatizados para as mesmas

## O que é o Postman?

O Postman é uma plataforma popular para o desenvolvimento e teste de APIs (Interfaces de Programação de Aplicações). 
Ele oferece uma variedade de ferramentas que facilitam a criação, compartilhamento, testes e documentação de APIs.

site oficial para donwload da ferramenta: https://www.postman.com/

## Configurando o Postman para testes na APIs

1. Navegue até o hub de APIs públicas no postman:  https://www.postman.com/explore

2. Procure por Postman Library API v2
![Explore](https://github.com/tatarv/API-Testing-Project/blob/main/2.%20Postman/screenshots/Postman_explore.png)

3. Dentro do workspace, vá para a area de coleções, clice no menu de contexto e escolha a opção fork
![Fork](https://github.com/tatarv/API-Testing-Project/blob/main/2.%20Postman/screenshots/Postman_fork.png)

4. Ou, se preferir crie uma coleção do 0 e crie uma variável que contenha o link da API:
![Variables](https://github.com/tatarv/API-Testing-Project/blob/main/2.%20Postman/screenshots/Postman_variables.png)

5. Preencha as URL's das requisições
![Collections](https://github.com/tatarv/API-Testing-Project/blob/main/2.%20Postman/screenshots/Postman_colection.png)


5. Pronto, pode começar a executar

Observação: Segundo a documentação, os livros cadastrados são apagados após 3 dias, então se certifique que o livro que está sendo
pesquisado, alterado, excluído ainda existe na base de dados para que todas as requisições e testes automatizados funcionem corretamente