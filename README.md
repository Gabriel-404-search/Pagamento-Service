Pagamento-Service 📟

Serviço de pagamento desenvolvido com Java e Spring Boot, utilizando arquitetura de microsserviços, mensageria com RabbitMQ, segurança com JWT e testes unitários. Esse projeto foi parte de um ecossistema maior, onde o objetivo era simular um fluxo real de compras.

🔧 Tecnologias utilizadas

Java 17

Spring Boot

Spring Security (JWT)

RabbitMQ

JUnit (Testes Unitários)

Docker

Maven

🔗 Integração com outros microserviços

RabbitMQ é utilizado para comunicação entre os serviços Produto-Service, Estoque-Service e Pagamento-Service.

🔐 Segurança com JWT

Implementação de autenticação e autorização com JWT.

Filtros e configurações customizadas de segurança.

✅ Funcionalidades

Criar pagamentos e registrar pedidos com validação de dados

Processamento baseado em Strategy Pattern (Pix, Cartão, Boleto)

Tratamento global de exceções com @ControllerAdvice

Integração com outros serviços via eventos

Documentação com Swagger

📊 Testes

Testes unitários para as regras de negócio e serviços

📆 Como executar

# Build do projeto
mvn clean install

# Executar o JAR
target/pagamento-service.jar

📂 Estrutura de pacotes

src/
├── controller
├── dto
├── entity
├── repository
├── service
├── config
├── security
└── enums

👨‍💻 Autor

Gabriel Marques da SilvaLinkedInGitHub

