# My App

Projeto full stack utilizando TypeScript, Node.js, React e Docker.

## Estrutura do Projeto

### Backend

- **controllers/**: Controladores da aplicação.
  - `customerController.ts`: Controlador para operações relacionadas a clientes.
- **config/**: Configurações da aplicação.
  - `database.ts`: Configuração do banco de dados.
- **models/**: Modelos de dados da aplicação.
  - `Customer.ts`: Modelo para dados de clientes.
- **routes/**: Rotas da aplicação.
  - `customerRoutes.ts`: Rotas relacionadas a clientes.
  - `routeRoutes.ts`: Rotas relacionadas a rotas.
- **services/**: Serviços da aplicação.
  - `externalApiService.ts`: Serviço para interagir com uma API externa.
- `app.ts`: Configuração principal da aplicação.
- `server.ts`: Arquivo principal para iniciar o servidor.
- `Dockerfile`: Dockerfile para o backend.

### Database

- `create_table_customers.sql`: Script SQL para criação da tabela de clientes.
- `Dockerfile`: Dockerfile para o banco de dados.

### Frontend

- **components/**: Componentes React reutilizáveis.
  - `CustomerList.tsx`: Componente para listar clientes.
  - `CustomerForm.tsx`: Componente para formulário de cliente.
  - `RouteCalculator.tsx`: Componente para calcular a melhor rota.
- **pages/**: Páginas React.
  - `CustomersPage.tsx`: Página para gerenciar clientes.
  - `RoutePage.tsx`: Página para calcular a melhor rota.
- `App.tsx`: Arquivo principal do aplicativo React.
- `Dockerfile`: Dockerfile para o frontend.

### Docker Compose

- `docker-compose.yml`: Arquivo de configuração do Docker Compose para orquestrar os contêineres.

## Instruções para Execução

1. Certifique-se de ter o Docker e o Docker Compose instalados.
2. Clone este repositório: `git clone https://github.com/seu-usuario/my-app.git`
3. Navegue até o diretório do projeto: `cd my-app`
4. Execute a aplicação com o Docker Compose: `docker-compose up`
5. Acesse a aplicação no navegador: `http://localhost:3000`

## Contribuindo

Abra issues para sugestões, problemas ou melhorias. Pull requests são bem-vindos!
