# 🔧 Mocked CRUD with Request Body

Este projeto é uma API RESTful simples desenvolvida com **Spring Boot**, simulando operações de CRUD em memória (mockado), usando o corpo da requisição (`@RequestBody`) para envio e recebimento de dados.

> 💡 Ideal para quem está aprendendo a construir APIs REST com Java e Spring Boot.

---

## 🚀 Tecnologias utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Maven
- YAML para configuração
- JUnit (estrutura de testes)
- IDE: IntelliJ IDEA

---

## 📦 Funcionalidades

- ✅ Criar pessoa (`POST /person`)
- ✅ Listar pessoas (`GET /person`)
- ✅ Buscar por ID (`GET /person/{id}`)
- ✅ Atualizar pessoa (`PUT /person/{id}`)
- ✅ Deletar pessoa (`DELETE /person/{id}`)

Os dados são armazenados apenas em memória (não persiste após reiniciar a aplicação).

---

## 📄 Exemplos de Requisição

### Criar Pessoa

```http
POST /person
Content-Type: application/json

{
    "firstName": "Murilo",
    "lastName": "Santiago",
    "address": "São Paulo - SP",
    "gender": "Masculino"
}
