# CRUD API com NestJS

Este é um projeto básico de uma API CRUD (Create, Read, Update, Delete) desenvolvido com o framework NestJS. Esta aplicação foi criada sem persistência de dados, ou seja, os dados manipulados estão apenas em memória e serão perdidos ao reiniciar o servidor.

## Tecnologias Utilizadas
- **NestJS**: Framework Node.js para construção de aplicativos back-end eficientes e escaláveis.
- **TypeScript**: Linguagem que adiciona tipagem ao JavaScript, facilitando o desenvolvimento e a manutenção.

## Funcionalidades

A API fornece operações básicas de CRUD para um recurso de exemplo. As rotas principais incluem:

- **Criar**: Adicionar um novo item.
- **Listar**: Obter uma lista de todos os itens.
- **Visualizar**: Obter detalhes de um item específico.
- **Atualizar**: Modificar as informações de um item específico.
- **Excluir**: Remover um item.

### Exemplo de Rotas

| Método | Rota                  | Descrição                            |
|--------|-----------------------|--------------------------------------|
| POST   | `/items`              | Criar um novo item                   |
| GET    | `/items`              | Listar todos os itens                |
| GET    | `/items/:id`          | Obter detalhes de um item específico |
| PATCH  | `/items/:id`          | Atualizar um item específico         |
| DELETE | `/items/:id`          | Excluir um item                      |

> **Nota**: Como não há persistência de dados, todas as alterações são temporárias e os dados serão redefinidos ao reiniciar o servidor.

## Instalação

Siga os passos abaixo para rodar o projeto localmente:

1. Clone o repositório:

    ```bash
    git clone https://github.com/augustoreimberg/CRUD-NestJS.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd CRUD-NestJS
    ```

3. Instale as dependências:

    ```bash
    npm install
    ```

4. Inicie o servidor:

    ```bash
    npm run start
    ```

O servidor estará rodando em [http://localhost:3000](http://localhost:3000).

## Estrutura do Projeto

A estrutura básica do projeto NestJS segue o padrão de organização de módulos


