# API (Interface de Programação de Aplicações) de Tarefa
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37.svg?style=for-the-badge&logo=Postman&logoColor=white)

Este projeto é uma API (Interface de Programação de Aplicações) para um sistema de gerenciamento de tarefas, onde cada tarefa deve ter um título, uma descrição e uma data de vencimento. Os usuários podem criar, editar e excluir tarefas, que serão operações CRUD, utilizando JAVA, Spring Boot, com documenção Swagger, conforme solicitado nos exercícios do Curso TI 360 TECH - Formação de Profissional 4.0, do Weslley Borges - Executivo de TI, para obter maior conhecimento na linguagem.

## Responsabilidades da API (Interface de Programação de Aplicações)
- Retornar uma lista de todas as tarefas cadastradas,
- Retornar uma lista de todas as tarefas cadastradas, filtrando por código, retornando "OK - Tarefa Encontrada", "ERRO - Tarefa não localizada" ou "Erro Inesperado,
- Cadastrar novas tarefas,
- Excluir tarefa cadastrada.

## Ferramenta utilizada para realização de testes
Para verificar se o código estava funcionando corretamente foi utilizada as Ferramentas POSTMAN e SWAGGER, apresentando a mensagem abaixo relacionada no Body do cadastro:

{
    
    "id": 1,
    "Título": "Teste",
    "Descrição": "Teste",
    "date": "10/05/2025"    
}




