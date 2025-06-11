# Jutsu API 🍥

> Uma API REST com tema de Naruto, desenvolvida com Java e Spring Boot. Permite gerenciar times de ninjas, calcular scores de poder e atribuir missões, utilizando dados da Dattebayo API.

---

## 🚀 Sobre o Projeto

Este projeto é uma API RESTful criada para fãs do universo de Naruto. A ideia central é consumir informações de personagens da [Dattebayo API](https://dattebayo-api.onrender.com/) e adicionar uma camada de lógica de negócio própria, permitindo que os usuários criem e gerenciem seus próprios times de ninjas, avaliem a força desses times e os enviem em missões.

É uma excelente oportunidade para praticar conceitos de desenvolvimento backend com Java, como:
- Construção de APIs REST com Spring Boot.
- Persistência de dados com Spring Data JPA.
- Consumo de APIs externas com `WebClient`.
- Modelagem de dados e arquitetura em camadas.

## ✨ Funcionalidades

- **🥷 Listar Ninjas:** Busca e exibe personagens diretamente da Dattebayo API.
- **🛡️ Criar e Gerenciar Times:** Monte seus times de ninjas personalizados e salve-os no banco de dados.
- **💥 Calcular Score de Poder:** Uma lógica customizada que calcula a força de um time baseado nos atributos de seus membros.
- **📜 Atribuir Missões:** Crie missões e atribua-as para seus times.

## 🛠️ Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3**
- **Spring Web**
- **Spring Data JPA**
- **Spring WebFlux (para o WebClient)**
- **Maven/Gradle**
- **PostgreSQL / H2 (Banco de Dados)**
- **Lombok**

## ⚙️ Como Começar

Para rodar este projeto localmente, você precisará ter as seguintes ferramentas instaladas:

### Pré-requisitos
- JDK 17 ou superior.
- Maven ou Gradle.
- Uma instância de banco de dados (como PostgreSQL) ou use o H2 (em memória) para testes.
- Uma ferramenta para testar APIs, como [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/).

### Instalação e Execução

1. Clone o repositório:
   ```sh
   git clone [https://github.com/seu-usuario/Jutsu-API.git](https://github.com/seu-usuario/Jutsu-API.git)

   Ótima escolha! "Jutsu API" é um nome excelente — curto, direto e muito temático.

Aqui estão os dois modelos de README, agora atualizados com o nome Jutsu API. É só copiar e colar o conteúdo no arquivo README.md do seu repositório no GitHub.

Versão em Português 🇧🇷
Markdown

# Jutsu API 🍥

> Uma API REST com tema de Naruto, desenvolvida com Java e Spring Boot. Permite gerenciar times de ninjas, calcular scores de poder e atribuir missões, utilizando dados da Dattebayo API.

---

## 🚀 Sobre o Projeto

Este projeto é uma API RESTful criada para fãs do universo de Naruto. A ideia central é consumir informações de personagens da [Dattebayo API](https://dattebayo-api.onrender.com/) e adicionar uma camada de lógica de negócio própria, permitindo que os usuários criem e gerenciem seus próprios times de ninjas, avaliem a força desses times e os enviem em missões.

É uma excelente oportunidade para praticar conceitos de desenvolvimento backend com Java, como:
- Construção de APIs REST com Spring Boot.
- Persistência de dados com Spring Data JPA.
- Consumo de APIs externas com `WebClient`.
- Modelagem de dados e arquitetura em camadas.

## ✨ Funcionalidades

- **🥷 Listar Ninjas:** Busca e exibe personagens diretamente da Dattebayo API.
- **🛡️ Criar e Gerenciar Times:** Monte seus times de ninjas personalizados e salve-os no banco de dados.
- **💥 Calcular Score de Poder:** Uma lógica customizada que calcula a força de um time baseado nos atributos de seus membros.
- **📜 Atribuir Missões:** Crie missões e atribua-as para seus times.

## 🛠️ Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3**
- **Spring Web**
- **Spring Data JPA**
- **Spring WebFlux (para o WebClient)**
- **Maven/Gradle**
- **PostgreSQL / H2 (Banco de Dados)**
- **Lombok**

## ⚙️ Como Começar

Para rodar este projeto localmente, você precisará ter as seguintes ferramentas instaladas:

### Pré-requisitos
- JDK 17 ou superior.
- Maven ou Gradle.
- Uma instância de banco de dados (como PostgreSQL) ou use o H2 (em memória) para testes.
- Uma ferramenta para testar APIs, como [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/).

### Instalação e Execução

1. Clone o repositório:
  
2. Navegue até a pasta do projeto:
   cd Jutsu-API
   
3. Configure suas variáveis de ambiente (se necessário), como as credenciais do banco de dados no arquivo application.properties.

4. Execute o projeto com o Maven:
   ./mvnw spring-boot:run
   
6. A API estará disponível em http://localhost:8080.

🗺️ Endpoints da API:
GET	/api/ninjas	Lista ninjas da API externa.
GET	/api/ninjas/{id}	Busca um ninja específico por ID.
POST	/api/teams	Cria um novo time de ninjas.
GET	/api/teams/{id}	Busca um time e calcula seu score de poder.
POST	/api/missions	Cria uma nova missão.
PUT	/api/missions/{id}/assign	Atribui um time a uma missão existente.

Claro! Ter um único arquivo com as duas linguagens é uma prática excelente para repositórios internacionais. A melhor forma de fazer isso é com um pequeno seletor no topo que direciona para a seção de cada idioma.

Aqui está o conteúdo para um único arquivo README.md que contém as duas linguagens. É só copiar e colar no seu repositório.

Markdown

# Jutsu API 🍥

> Uma API REST com tema de Naruto, desenvolvida com Java e Spring Boot.
>
> A Naruto-themed REST API built with Java and Spring Boot.

[Versão em Português 🇧🇷](#-versão-em-português) | [English Version 🇺🇸](#-english-version)

---

## 🇧🇷 Versão em Português

### 🚀 Sobre o Projeto

Este projeto é uma API RESTful criada para fãs do universo de Naruto. A ideia central é consumir informações de personagens da [Dattebayo API](https://dattebayo-api.onrender.com/) e adicionar uma camada de lógica de negócio própria, permitindo que os usuários criem e gerenciem seus próprios times de ninjas, avaliem a força desses times e os enviem em missões.

É uma excelente oportunidade para praticar conceitos de desenvolvimento backend com Java, como:
- Construção de APIs REST com Spring Boot.
- Persistência de dados com Spring Data JPA.
- Consumo de APIs externas com `WebClient`.
- Modelagem de dados e arquitetura em camadas.

### ✨ Funcionalidades

- **🥷 Listar Ninjas:** Busca e exibe personagens diretamente da Dattebayo API.
- **🛡️ Criar e Gerenciar Times:** Monte seus times de ninjas personalizados e salve-os no banco de dados.
- **💥 Calcular Score de Poder:** Uma lógica customizada que calcula a força de um time baseado nos atributos de seus membros.
- **📜 Atribuir Missões:** Crie missões e atribua-as para seus times.

### 🛠️ Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3**
- **Spring Web**
- **Spring Data JPA**
- **Spring WebFlux (para o WebClient)**
- **Maven/Gradle**
- **PostgreSQL / H2 (Banco de Dados)**
- **Lombok**

### ⚙️ Como Começar

Para rodar este projeto localmente, você precisará ter as seguintes ferramentas instaladas:

#### Pré-requisitos
- JDK 17 ou superior.
- Maven ou Gradle.
- Uma instância de banco de dados (como PostgreSQL) ou use o H2 (em memória) para testes.
- Uma ferramenta para testar APIs, como [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/).

#### Instalação e Execução

1. Clone o repositório:
   git clone 
Navegue até a pasta do projeto:

Bash

cd Jutsu-API
Configure suas variáveis de ambiente (se necessário), como as credenciais do banco de dados no arquivo application.properties.

Execute o projeto com o Maven:

Bash

./mvnw spring-boot:run
Ou com o Gradle:

Bash

./gradlew bootRun
A API estará disponível em http://localhost:8080.

🗺️ Endpoints da API
Método	Rota	Descrição
GET	/api/ninjas	Lista ninjas da API externa.
GET	/api/ninjas/{id}	Busca um ninja específico por ID.
POST	/api/teams	Cria um novo time de ninjas.
GET	/api/teams/{id}	Busca um time e calcula seu score de poder.
POST	/api/missions	Cria uma nova missão.
PUT	/api/missions/{id}/assign	Atribui um time a uma missão existente.


🙏 Agradecimentos
Um grande obrigado à [Dattebayo API](https://dattebayo-api.onrender.com/) por fornecer os dados dos personagens. 
