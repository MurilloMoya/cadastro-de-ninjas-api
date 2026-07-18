# 🥷 Cadastro de Ninjas API

> ⚠️ **Projeto em andamento.** Algumas funcionalidades planejadas, como persistência de dados, ainda estão sendo implementadas. Este README será atualizado conforme o desenvolvimento avança.

API RESTful desenvolvida em Java com Spring Boot para gerenciamento de cadastro de ninjas, seguindo arquitetura em camadas (Controller, Service, Repository).

## 🛠️ Tecnologias

- Java 21
- Spring Boot 4.1.0
- Spring Web (`spring-boot-starter-webmvc`)
- Maven

## 📌 Status atual

- [x] Estrutura do projeto (Spring Initializr)
- [x] Configuração de pacotes seguindo convenção Java (`br.com.murillomoya`)
- [x] Camada de Controller
- [x] Camada de Service
- [ ] Persistência de dados (JPA + banco de dados)
- [ ] Testes automatizados
- [ ] Documentação da API (Swagger/OpenAPI)

## 🏗️ Arquitetura

O projeto segue o padrão em camadas, separando responsabilidades:

- **Controller**: recebe as requisições HTTP e retorna as respostas
- **Service**: concentra as regras de negócio
- **Repository**: responsável pelo acesso aos dados *(em implementação)*

Atualmente, os dados dos ninjas são mantidos em memória, sem persistência em banco de dados — essa é a próxima etapa planejada do projeto.

## ▶️ Como executar

```bash
git clone https://github.com/MurilloMoya/cadastro-de-ninjas-api.git
cd cadastro-de-ninjas-api
mvn spring-boot:run
```

A aplicação sobe por padrão em `http://localhost:8080`.

## 📚 Contexto

Este projeto foi desenvolvido como exercício de aprendizado em Java e Spring Boot, com foco em fixar conceitos de arquitetura em camadas, boas práticas de nomenclatura e organização de uma API REST desde a estrutura inicial.

---

Projeto de estudo — em desenvolvimento contínuo.
