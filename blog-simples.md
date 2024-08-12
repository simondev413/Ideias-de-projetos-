# Blog Simples

## Descrição do Projeto

O projeto **Blog Simples** é uma aplicação web básica que permite aos usuários criar, editar e excluir posts. Cada post contém um título, conteúdo, data de publicação, e pode ser visualizado em uma página separada. Este projeto é ideal para quem está começando a explorar o desenvolvimento web, pois aborda conceitos fundamentais como CRUD (Create, Read, Update, Delete), roteamento, e renderização de templates.

## Funcionalidades Principais

1. **Listagem de Posts**:
   - Exibe uma lista de todos os posts existentes, organizados por data de publicação.
   - A partir da lista, o usuário pode clicar em um post para visualizar seus detalhes.

2. **Criação de Posts**:
   - Permite aos usuários criar novos posts, fornecendo um título e conteúdo.
   - Cada post é salvo com a data e hora de criação.

3. **Edição de Posts**:
   - Usuários podem editar posts existentes.
   - A data de última modificação é atualizada automaticamente.

4. **Exclusão de Posts**:
   - Permite aos usuários excluir posts.

5. **Visualização de Post Individual**:
   - Cada post pode ser visualizado em uma página separada com seu título, conteúdo, e data de publicação.

## Tecnologias Sugeridas

- **Back-end**:
  - **Flask** (Python): Um microframework simples e eficiente para criar aplicações web.
  - **Express.js** (Node.js): Um framework minimalista para Node.js, adequado para construir APIs e aplicativos web.

- **Front-end**:
  - **HTML**: Para a estrutura básica da página.
  - **CSS**: Para estilização das páginas.
  - **JavaScript**: Para interatividade básica e manipulação do DOM.

- **Banco de Dados**:
  - **SQLite**: Um banco de dados leve e fácil de configurar, ideal para projetos simples e para desenvolvimento.

## Instruções de Instalação

### Requisitos

- **Python 3.x** (para Flask)
- **Node.js** (para Express.js)
- **SQLite** (incluído no Python por padrão)

### Passos

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/blog-simples.git
    cd blog-simples
    ```

2. Escolha o back-end desejado (Flask ou Express.js) e siga as instruções abaixo:

#### Flask (Python)

1. Crie e ative um ambiente virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate  # Windows
    ```

2. Instale as dependências:
    ```bash
    pip install flask
    ```

3. Execute a aplicação:
    ```bash
    flask run
    ```

4. Acesse a aplicação no navegador em `http://localhost:5000`.

#### Express.js (Node.js)

1. Instale as dependências:
    ```bash
    npm install
    ```

2. Execute a aplicação:
    ```bash
    npm start
    ```

3. Acesse a aplicação no navegador em `http://localhost:3000`.

## Estrutura de Arquivos

```
blog-simples/
│
├── app.py (Flask) ou index.js (Express.js)  # Arquivo principal do servidor
├── templates/  # Arquivos HTML para renderização de páginas
│   ├── base.html  # Layout base do site
│   ├── index.html  # Página inicial com a lista de posts
│   ├── post.html  # Página de visualização de um post individual
│   ├── create_post.html  # Formulário de criação de post
│   └── edit_post.html  # Formulário de edição de post
├── static/
│   ├── css/  # Arquivos CSS
│   └── js/  # Arquivos JavaScript
└── database.db  # Banco de dados SQLite
```

## Exemplo de Uso

- **Página Inicial**: Exibe todos os posts, permitindo acesso rápido aos detalhes de cada um.
- **Novo Post**: Através de um formulário, o usuário pode criar novos posts.
- **Editar Post**: A partir da lista ou da visualização de um post, é possível editá-lo.
- **Excluir Post**: Usuários podem excluir posts indesejados diretamente da lista ou da visualização do post.

## Tarefas Futuras

- **Sistema de Comentários**: Implementar a funcionalidade para que os usuários comentem nos posts.
- **Autenticação de Usuários**: Adicionar um sistema de login para que apenas usuários registrados possam criar ou editar posts.
- **Busca e Filtros**: Implementar uma barra de pesquisa e filtros para facilitar a navegação entre os posts.

## Contribuindo

Contribuições são bem-vindas! Se você tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir um pull request ou uma issue.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## Contato

Para dúvidas ou sugestões, entre em contato:

- **Nome**: Simão Domingos De Oliveira António
- **Email**: simaodomingos413@gmail.com

---

Este projeto é uma excelente introdução ao desenvolvimento web, abordando conceitos fundamentais de forma prática e acessível.
