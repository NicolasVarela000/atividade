# Web Service REST - Empresas, Estudantes e Vagas

## 📌 Descrição

Este projeto é um Web Service REST desenvolvido com Spring Boot para gerenciar:

* Empresas
* Estudantes
* Vagas

Os dados são armazenados em memória utilizando listas.

---

## 🚀 Tecnologias utilizadas

* Java
* Spring Boot
* Maven
* REST API

---

## ▶️ Como executar o projeto

1. Clone o repositório:

```
git clone https://github.com/SEU-USUARIO/SEU-REPO.git
```

2. Acesse a pasta:

```
cd SEU-REPO
```

3. Execute o projeto:

```
./mvnw spring-boot:run
```

4. Acesse no navegador:

```
http://localhost:8080
```

---

## 🔗 Endpoints

### 📦 Empresas

* GET /empresas → Lista todas as empresas
* POST /empresas → Cadastra uma empresa
* PUT /empresas/{id} → Atualiza uma empresa
* DELETE /empresas/{id} → Remove uma empresa

---

### 🎓 Estudantes

* GET /estudantes
* POST /estudantes
* PUT /estudantes/{id}
* DELETE /estudantes/{id}

---

### 💼 Vagas

* GET /vagas
* POST /vagas
* PUT /vagas/{id}
* DELETE /vagas/{id}

---

## 📥 Exemplo de requisição (POST)

### Criar Estudante

```
POST /estudantes
Content-Type: application/json
```

```json
{
  "id": 11,
  "nome": "Novo Estudante",
  "email": "novo@email.com",
  "nascimento": "2000-01-01",
  "anoIngresso": 2024
}
```

---

## 🧪 Testes

Os testes podem ser feitos utilizando:

* REST Client (VS Code)
* Postman

Arquivos `.http` estão disponíveis em:

```
src/main/resources/http
```

---

## 🏷️ Versão

Tag do projeto:

```
B2-LAB1
```

---

## 👨‍💻 Autor

Projeto desenvolvido para atividade prática de Web Service REST com Spring Boot.
