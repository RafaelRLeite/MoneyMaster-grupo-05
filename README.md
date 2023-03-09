# MoneyMaster - Sistema de Gerenciamento de Finanças
    O Master Money é um sistema de gerenciamento de finanças desenvolvido em Java, que utiliza a arquitetura de 
    microserviços com Spring, integrado com serviços da AWS, MySQL e Docker. Ele possui uma interface de usuário 
    web utilizando HTML5, CSS3 e Angular, e utiliza testes unitários com JUnit e Mockito para garantir a qualidade 
    do código. Além disso, o projeto é gerenciado pelo GIT e hospedado no GitHub como um repositório open source. O 
    objetivo do Master Money é ajudar as pessoas a gerenciar suas finanças de forma mais eficiente, permitindo que 
    elas tenham uma visão clara de seus gastos e receitas.
---

## Funcionalidades
    * Cadastro de usuário
    * Login de usuário
    * Cadastro de contas
    * Cadastro de categorias de despesas e receitas
    * Lançamento de despesas e receitas
    * Visualização de saldo
    * Relatório de despesas e receitas
    * Integração com AWS
    * Utilização de Docker para deploy
    * Utilização de HTML5, CSS3 e Angular para a interface do usuário
    * Utilização de Junit e Mockito para testes automatizados
    * Controle de versão utilizando GIT e GitHub para gerenciamento de projetos  
---
## Tecnologias utilizadas
    * Java
    * Spring
    * AWS
    * MySQL
    * Docker
    * HTML5
    * CSS3
    * Angular
    * Junit
    * Mockito
    * GIT
    * GitHub
---
## Como executar
Para executar o sistema, é necessário ter instalado as seguintes tecnologias:

- Backend: **[Java](https://openjdk.java.net/install/)**
- Gerenciador de Depêndencias: **[Maven](https://maven.apache.org/download.cgi)**
- Conteinerização: **[Docker](https://docs.docker.com/get-docker/)**

Com as tecnologias instaladas, siga os seguintes passos:

---
## Clone o repositório do GitHub:

```
git clone https://github.com/Javeiros-brasil/MoneyMaster-grupo-05
```

## Navegue para o diretório do projeto:
```
cd MoneyMaster-grupo-05
```
## Construa o projeto com o Maven:
```
mvn clean install
```
## Execute o Docker Compose:
```
docker-compose up
```
## Acesse o sistema no navegador:
```
http://localhost:8080
```
---

## Como contribuir
    Faça um fork deste repositório
         - Crie uma branch para a sua feature: 
                git checkout -b feature/nova-feature
        - Faça as suas alterações e commit: 
                git commit -m 'Adiciona nova feature'
        - Push para o branch: 
                 git push origin feature/nova-feature
        - Abra um pull request

---
## Licença
    Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE
    para obter mais informações.
