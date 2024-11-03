# Loja de Roupas - Sistema de Gestão

## Descrição do Projeto

Este projeto é um sistema de gestão para uma loja de roupas, desenvolvido em Java com a estrutura MVC. O sistema possibilita gerenciar todas as operações essenciais para o funcionamento de uma loja, como compra de produtos, pagamentos, cadastro de funcionários, clientes e seus dependentes, além do controle de faturamento.

## Funcionalidades

- **Gestão de Produtos**: permite adicionar, atualizar, listar e remover produtos do inventário da loja.
- **Processamento de Compras**: realiza compras de produtos com integração de métodos de pagamento.
- **Gerenciamento de Funcionários**: permite o cadastro e gerenciamento dos funcionários da loja.
- **Cadastro de Clientes e Dependentes**: organiza e mantém registros dos clientes e de seus dependentes.
- **Controle de Faturamento**: gera relatórios e permite o monitoramento do faturamento, auxiliando a análise financeira e tomada de decisões.

## Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **JPA/Hibernate**: para o mapeamento objeto-relacional e gerenciamento do banco de dados.
- **MySQL**: banco de dados para armazenamento das informações.
- **Thymeleaf**: motor de templates para renderização do front-end.
- **Materialize CSS**: framework de CSS para estilização e design responsivo.

## Estrutura do Projeto

Este projeto foi desenvolvido utilizando a arquitetura MVC (Model-View-Controller), organizando o código para separar as responsabilidades de manipulação dos dados, regras de negócio e interface com o usuário.

- `src/main/java`: contém os pacotes com as classes de domínio, serviços, controladores e repositórios.
- `src/main/resources/templates`: contém os templates Thymeleaf para renderização das páginas HTML.
- `src/main/resources/static`: contém os arquivos de estilo CSS e JavaScript, incluindo Materialize para estilização.

## Pré-requisitos

Para executar o projeto, é necessário ter os seguintes itens instalados:

- **Java JDK 11** ou superior
- **MySQL**
- **Maven** (ou outra ferramenta de build compatível com Spring Boot)

## Configuração do Projeto

1. Clone o repositório para sua máquina local.
    ```bash
    git clone https://github.com/Death-Chronos/LojaRoupas.git
    ```

2. Configure o banco de dados MySQL e atualize o arquivo `application.properties` em `src/main/resources/` com as credenciais de acesso.
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/loja_roupas
    spring.datasource.username=seu-usuario
    spring.datasource.password=sua-senha
    spring.jpa.hibernate.ddl-auto=update
    ```

3. Execute o projeto usando o Maven:
    ```bash
    mvn spring-boot:run
    ```

4. Acesse o sistema pelo navegador:
    ```
    http://localhost:8080
    ```

## Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/minha-feature`)
3. Commit suas alterações (`git commit -m 'Adicionei minha feature'`)
4. Envie para o branch (`git push origin feature/minha-feature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
