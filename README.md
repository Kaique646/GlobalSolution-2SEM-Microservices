# GlobalSolution-2SEM-Microservices

# Projeto Spring Boot com JDK 17 e MySQL

Este é um projeto Spring Boot configurado com JDK 17 e MySQL, projetado para fornecer endpoints para manipulação de Objetivos e Indicadores.

## Configurações do Projeto

- **JDK**: 17
- **Spring Boot**: v3.1.5
- **MySQL**

Certifique-se de ter essas configurações instaladas em seu ambiente antes de executar o projeto.

## Configuração do Banco de Dados

O projeto utiliza o MySQL como banco de dados. Certifique-se de criar um banco de dados com o nome desejado e ajuste as configurações de conexão no arquivo `application.properties` conforme necessário.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/seu_banco_de_dados
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha


```markdown
## Endpoints

### Objetivos

- **Endpoint**: `/objetivos`
  - **Método**: GET
  - **Descrição**: Recupera todos os objetivos.
  - **Exemplo**: `http://localhost:8080/objetivos`

  ![Objetivos Endpoint](link_da_imagem_objetivos)

### Indicadores por ID

- **Endpoint**: `/indicadores/{id}`
  - **Método**: GET
  - **Descrição**: Recupera os indicadores para um determinado ID.
  - **Exemplo**: `http://localhost:8080/indicadores/1`

  ![Indicadores por ID Endpoint](link_da_imagem_indicadores)

## Como Executar o Projeto

1. Clone o repositório para o seu ambiente local.
2. Certifique-se de ter o JDK 17 instalado.
3. Configure o banco de dados no arquivo `application.properties`.
4. Execute o projeto usando sua IDE favorita ou o comando Maven: `mvn spring-boot:run`.

Agora você pode acessar os endpoints mencionados acima.

**Observação**: As imagens dos endpoints fornecidas são apenas exemplos e devem ser substituídas pelos links reais do seu ambiente local. Certifique-se de gerar essas imagens para uma documentação mais precisa.

Este é um projeto inicial e pode ser expandido conforme necessário para atender aos requisitos específicos do seu curso. Boa codificação!