# To-Do List com Autenticação

## Descrição do Projeto

Este projeto consiste em uma aplicação simples de lista de tarefas (To-Do List) que inclui recursos de autenticação e autorização de usuários. O objetivo é permitir que cada usuário tenha sua própria lista de tarefas, podendo adicionar, editar, excluir e marcar as tarefas como concluídas. É um projeto ideal para desenvolvedores que desejam praticar a criação de aplicativos com autenticação e gerenciamento de dados personalizados.

## Funcionalidades Principais

1. **Autenticação de Usuários**:
   - Registro de novos usuários.
   - Login e logout de usuários registrados.
   - Recuperação de senha via e-mail.

2. **Gerenciamento de Tarefas**:
   - Usuários podem criar novas tarefas, editar o título e a descrição, e definir uma data de conclusão.
   - Tarefas podem ser marcadas como concluídas ou removidas da lista.
   - Organização de tarefas por status (concluídas ou pendentes).

3. **Categorias de Tarefas**:
   - Usuários podem criar categorias personalizadas para organizar suas tarefas.
   - Visualização de tarefas por categoria.

4. **Prioridade das Tarefas**:
   - As tarefas podem ter níveis de prioridade (alta, média, baixa).
   - Ordenação de tarefas por prioridade.

5. **Pesquisa e Filtros**:
   - Filtro de tarefas por status, prioridade ou categoria.
   - Barra de pesquisa para encontrar tarefas específicas.

## Tecnologias Sugeridas

- **Back-end**:
  - **Linguagem**: Python
  - **Framework**: Django ou Flask
  - **Autenticação**: Django Authentication, Flask-Login
  - **Banco de Dados**: SQLite (para desenvolvimento) ou PostgreSQL
  - **ORM**: Django ORM, SQLAlchemy

- **Front-end**:
  - **Linguagem**: HTML, CSS, JavaScript
  - **Bibliotecas/Frameworks**: Bootstrap, jQuery, ou um framework front-end moderno como React.js

## Instruções de Instalação

### Requisitos

- **Python 3.x**
- **SQLite** (para desenvolvimento) ou **PostgreSQL** (para produção)
- **Node.js** (se for utilizar React.js ou outro framework front-end moderno)

### Passos

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/todo-list-com-autenticacao.git
    cd todo-list-com-autenticacao
    ```

2. Crie e ative um ambiente virtual:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate  # Windows
    ```

3. Instale as dependências do back-end:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure o banco de dados:
    - No caso do SQLite, o banco de dados já estará configurado por padrão.
    - Se estiver usando PostgreSQL, atualize o arquivo `settings.py` (Django) ou `config.py` (Flask) com as credenciais do banco de dados.

5. Aplique as migrações para criar as tabelas no banco de dados:
    ```bash
    python manage.py migrate  # Django
    flask db upgrade  # Flask
    ```

6. Inicie o servidor de desenvolvimento:
    ```bash
    python manage.py runserver  # Django
    flask run  # Flask
    ```

7. Acesse o aplicativo no navegador em `http://localhost:8000`.

### (Opcional) Passos para o Front-end

1. Navegue até o diretório do front-end (separado do back-end):
    ```bash
    cd frontend
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Inicie o servidor de desenvolvimento do front-end:
    ```bash
    npm start
    ```

## Exemplo de Uso

- **Registro/Login**: Usuários criam uma conta ou fazem login.
- **Adição de Tarefas**: Usuários adicionam novas tarefas com título, descrição e data de conclusão.
- **Organização**: Tarefas podem ser organizadas em categorias, filtradas por prioridade e marcadas como concluídas.
- **Gerenciamento de Tarefas**: Usuários editam ou removem tarefas conforme necessário.

## Tarefas Futuras

- **Notificações**: Implementar um sistema de notificações para lembrar os usuários de tarefas próximas ao prazo.
- **Compartilhamento de Tarefas**: Adicionar funcionalidade para permitir que usuários compartilhem tarefas com outros usuários.
- **Aplicativo Mobile**: Desenvolver uma versão mobile para Android e iOS usando React Native ou Flutter.
- **Sincronização com Calendário**: Integrar a aplicação com serviços de calendário como Google Calendar.

## Contribuindo

Contribuições são sempre bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir um pull request ou uma issue.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## Contato

Para dúvidas ou sugestões, entre em contato:

- **Nome**: Simão Domingos De Oliveira António
- **Email**: simaodomingos413@gmail.com

---

Este projeto é excelente para desenvolvedores que desejam aprender sobre autenticação de usuários e gerenciamento de dados em uma aplicação web.
