# 🎬 ScreenMatch API - Spring Boot + JPA

Projeto desenvolvido em Java com Spring Boot, focado em persistência de dados e consultas utilizando Spring Data JPA e PostgreSQL.

A aplicação permite o gerenciamento de séries e episódios, realizando cadastro, relacionamento entre entidades e consultas personalizadas no banco de dados.

---

## 🚀 Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- PostgreSQL
- Maven

---

## 📌 Funcionalidades implementadas

- Modelagem de entidades (Série e Episódio)
- Mapeamento de relacionamentos (OneToMany / ManyToOne)
- Persistência de dados com JPARepository
- Consultas derivadas
- Consultas personalizadas com JPQL
- Filtros por categoria, título e múltiplos critérios
- Ordenação e busca das top séries
- Uso de variáveis de ambiente para dados sensíveis

---

## ⚙️ Como executar o projeto

1. Clone o repositório
2. Configure as variáveis de ambiente:


- DB_HOST=
- DB_PORT=
- DB_NAME=
- DB_USER=
- DB_PASSWORD=
- API KEY (Na classe principal)
