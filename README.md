# 🚗 Controle de Estacionamento API

Uma API RESTful para gerenciar vagas de estacionamento em uma área residencial usando Spring Boot e PostgreSQL.

## 📋 Funcionalidades

- Criar, atualizar, deletar e buscar vagas de estacionamento.
- Validações para impedir entradas duplicadas com base na placa, número da vaga, apartamento e bloco.
- Paginação para listar registros de vagas.
- Gerencia detalhes do carro e do responsável.

## 📂 Endpoints

- **POST /parking-spot** - Registrar nova vaga.
- **GET /parking-spot** - Listar vagas com paginação.
- **GET /parking-spot/{id}** - Detalhar vaga por ID.
- **DELETE /parking-spot/{id}** - Remover vaga por ID.
- **PUT /parking-spot/{id}** - Atualizar vaga por ID.

## 🛠️ Tecnologias

- **Spring Boot**: Framework web.
- **PostgreSQL**: Banco de dados.
- **JPA**: ORM.
- **Jakarta Validation**: Validações.

## ⚙️ Configuração

Configure o arquivo `application.properties` com suas credenciais de banco de dados:


## 🚀 Rodando o Projeto

Execute o projeto com Maven:

```bash
./mvnw spring-boot:run
