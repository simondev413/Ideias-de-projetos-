# E-commerce Simples

## Descrição do Projeto

Este projeto visa a criação de uma plataforma básica de e-commerce. Ele permite que os usuários naveguem por produtos, adicionem itens ao carrinho de compras, realizem pagamentos e visualizem o histórico de pedidos. O projeto é ideal para desenvolvedores iniciantes que desejam aprender os fundamentos de uma aplicação de comércio eletrônico.

## Funcionalidades Principais

1. **Cadastro de Usuários**: 
   - Usuários podem criar uma conta, fazer login e atualizar suas informações pessoais.
   - Implementação de recuperação de senha via e-mail.

2. **Gerenciamento de Produtos**:
   - Administradores podem adicionar, editar e remover produtos.
   - Produtos são organizados em categorias para fácil navegação.
   - Suporte para múltiplas imagens por produto.

3. **Carrinho de Compras**:
   - Usuários podem adicionar produtos ao carrinho e alterar a quantidade de itens.
   - O carrinho exibe o total atualizado automaticamente.
   - Possibilidade de remover itens do carrinho.

4. **Checkout e Pagamento**:
   - Integração com um gateway de pagamento (Stripe, PayPal, etc.) para processar pagamentos.
   - Confirmação de pedido após o pagamento ser realizado com sucesso.
   - Opção para salvar endereços de entrega para compras futuras.

5. **Histórico de Pedidos**:
   - Os usuários podem visualizar uma lista de pedidos anteriores.
   - Detalhes do pedido, incluindo produtos comprados, quantidade e data de compra.

6. **Filtros e Pesquisa**:
   - Produtos podem ser filtrados por categoria, preço e popularidade.
   - Implementação de uma barra de pesquisa para encontrar produtos específicos.

## Tecnologias Sugeridas

- **Back-end**: 
  - **Linguagem**: Python
  - **Framework**: Django ou Flask
  - **Autenticação**: Django Authentication, Flask-Login
  - **Banco de Dados**: PostgreSQL, SQLite (para desenvolvimento)
  - **ORM**: Django ORM, SQLAlchemy

- **Front-end**:
  - **Linguagem**: HTML, CSS, JavaScript
  - **Bibliotecas/Frameworks**: Bootstrap, React.js ou Vue.js (opcional)

- **Integração de Pagamento**:
  - **API**: Stripe, PayPal

## Instruções de Instalação

### Requisitos

- **Python 3.x**
- **PostgreSQL** ou outro banco de dados compatível.
- **Node.js** (se for utilizar React.js ou Vue.js)

### Passos

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/ecommerce-simples.git
    cd ecommerce-simples
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

4. Configure o banco de dados PostgreSQL:
    - Crie um banco de dados no PostgreSQL para o projeto.
    - Atualize o arquivo `settings.py` (Django) ou `config.py` (Flask) com as credenciais do banco de dados.

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
- **Navegação de Produtos**: Usuários navegam pelos produtos usando filtros ou a barra de pesquisa.
- **Carrinho de Compras**: Usuários adicionam produtos ao carrinho e procedem ao checkout.
- **Pagamento**: Integração com um gateway de pagamento para finalizar a compra.
- **Histórico de Pedidos**: Usuários podem verificar o status e detalhes de suas compras passadas.

## Tarefas Futuras

- **Sistema de Avaliações**: Adicionar a possibilidade de usuários avaliarem e comentarem sobre os produtos.
- **Cupons de Desconto**: Implementar um sistema para aplicar cupons de desconto durante o checkout.
- **Notificações por E-mail**: Configurar e-mails automáticos para confirmação de pedidos e outras notificações.
- **Recomendações de Produtos**: Implementar um sistema de recomendação de produtos baseado em compras anteriores.

## Contribuindo

Contribuições são sempre bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir um pull request ou uma issue.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## Contato

Para dúvidas ou sugestões, entre em contato:

- **Nome**: Simão Domingos De Oliveira António
- **Email**: simaodomingos413@gmail.com
