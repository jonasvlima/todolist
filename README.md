# TodoList API

API para gerenciar tarefas de uma lista de afazeres (todo list). Desenvolvida para portfólio.

🚀 **Funcionalidades**
- Tarefas: Criar, visualizar, editar e deletar tarefas.

🛠 **Tecnologias**
- Java 21
- Spring Boot
- Docker (para deploy)
- H2 (Banco de dados em memória)
- Maven (Gerenciamento de dependências)
- Insomnia (Testes de API)

▶️ **Como Executar**

1. Clone o repositório:
   `git clone https://github.com/jonasvlima/todolist.git`

2. Acesse a pasta do projeto:
   `cd todolist`

3. Execute o projeto usando Docker:
   `docker-compose up --build`

   Ou, se preferir executar localmente sem Docker, use:
   `./mvnw spring-boot:run`

4. A API estará disponível em:
   `http://localhost:8080`

🔗 **Endpoints**

- **Tarefas:**
  - `POST /tasks`: Cria uma nova tarefa.
  - `GET /tasks/{id}`: Retorna uma tarefa específica.
  - `GET /tasks`: Retorna todas as tarefas.
  - `PUT /tasks/{id}`: Edita uma tarefa existente.
  - `DELETE /tasks/{id}`: Deleta uma tarefa.

🔮 **Melhorias Futuras**
- Adicionar autenticação de usuários.
- Implementar categorias para as tarefas.
- Adicionar validações para editar e deletar tarefas.
- Migrar para um banco de dados real (MySQL/PostgreSQL).

📞 **Contato**
- Nome: Jonas Lima
- GitHub: [jonasvlima](https://github.com/jonasvlima)
- LinkedIn: [Jonas Lima](https://www.linkedin.com/in/jonas-lima-212901261/)

🚀 **Projeto concluído!**
