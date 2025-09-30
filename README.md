# HexaERP

HexaERP é um projeto de sistema ERP (Enterprise Resource Planning) desenvolvido em Java utilizando o framework Spring Boot. O objetivo é fornecer uma base para sistemas de gestão empresarial, integrando módulos como financeiro, estoque, vendas, compras, entre outros.

## Funcionalidades (em desenvolvimento)
- Estrutura inicial para um sistema ERP
- Integração com banco de dados PostgreSQL
- Utilização de Spring Boot para web e persistência
- Testes automatizados com JUnit

## Estrutura do Projeto
```
pom.xml
src/
  main/
    java/
      br/com/hexacore/erp/  # Código principal
  test/
    java/
      br/com/hexacore/erp/  # Testes automatizados
```

## Principais Tecnologias
- Java 17
- Spring Boot (Web, Data JPA)
- PostgreSQL
- Lombok
- Maven
- JUnit

## Como rodar o projeto
1. Certifique-se de ter o Java 17 e o Maven instalados.
2. Configure o acesso ao banco de dados PostgreSQL no arquivo de propriedades (application.properties).
3. Execute o comando abaixo para compilar e rodar:
   ```shell
   mvn spring-boot:run
   ```

## Como executar os testes
```shell
mvn test
```

## Observações
- O projeto está em fase inicial e serve como base para expansão dos módulos ERP.
- Contribuições são bem-vindas!

## Licença
Este projeto está sob a licença MIT.
