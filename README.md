# 📌 Testes de API – JSONPlaceholder (Postman)

Este repositório contém um conjunto de **testes automatizados de API** desenvolvidos no **Postman**, utilizando a API pública **JSONPlaceholder**, com foco nos recursos **Posts** e **Comments**.

O projeto foi criado com o objetivo de demonstrar conhecimentos em **testes de API REST**, **validação de contrato**, **cenários positivos e negativos** e **organização de testes**, visando oportunidades de **estágio ou posição júnior em QA**.

---

## 🎯 Objetivo do Projeto

- Praticar testes de API REST
- Criar testes automatizados utilizando `pm.test`
- Validar estrutura, tipos de dados e comportamento das respostas
- Organizar testes de forma clara e escalável
- Simular um projeto real de QA para portfólio

---

## 🧪 Escopo dos Testes

### 🔹 Posts

Os testes cobrem os seguintes endpoints:

- `GET /posts`
- `GET /posts/{id}`
- `GET /posts?userId={userId}`
- `POST /posts`
- `PUT /posts/{id}`
- `DELETE /posts/{id}`

---

### 🔹 Comments

Os testes cobrem os seguintes endpoints:

- `GET /comments`
- `GET /comments/{id}`
- `GET /comments?postId={postId}`
- `POST /comments`
- `PUT /comments/{id}`
- `DELETE /comments/{id}`

---

## ✅ Tipos de Validações Implementadas

- Validação de **status code**
- Validação de **campos obrigatórios**
- Validação de **tipos de dados**
- Validação de **parâmetros de query**
- Validação de **listas vazias**
- Validação de **tempo de resposta**
- Cenários **positivos e negativos**
- Validação de **contrato da API**
- Testes para **recursos inexistentes**

---

## ⚠️ Observações Importantes

A API **JSONPlaceholder** é uma API de simulação (mock), o que implica que:

- Os dados **não são persistidos**
- Métodos `POST`, `PUT` e `DELETE` retornam sucesso mesmo em cenários inválidos
- Alguns cenários negativos **não retornam erros reais**

Essas limitações foram consideradas na definição e implementação dos casos de teste, que validam o **comportamento observado da API**.

---

## 🛠️ Ferramentas Utilizadas

- **Postman**
- **JavaScript**
- **Chai Assertions** (via `pm.expect`)

---

## ⚙️ Configuração do Projeto

- Todas as variáveis (URL base, IDs inválidos, parâmetros de query) estão definidas **no nível da Collection**
- Não é necessário configurar **Environment** para executar os testes

---

## ▶️ Como Executar os Testes

1. Importar a **Collection** no Postman
2. Selecionar a Collection
3. Executar as requisições manualmente ou utilizar o Collection Runner para executar todos os testes

---

## 👤 Autor

**Aquiles Araújo**  
Foco em QA / Testes de Software
