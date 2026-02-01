# 📌 Testes de API – JSONPlaceholder (Postman)

Este repositório contém um conjunto de **testes automatizados de API** desenvolvidos no **Postman**, utilizando a API pública **JSONPlaceholder**, com foco no recurso **Posts**.

O objetivo do projeto é demonstrar conhecimentos em **testes de API**, **validação de contrato**, **cenários positivos e negativos** e **organização de testes**, visando oportunidades como **estágio ou posição júnior em QA**.

---

## 🎯 Objetivo do Projeto

- Praticar testes de API REST
- Aplicar validações automatizadas com `pm.test`
- Estruturar casos de teste de forma organizada
- Simular um projeto real de QA para portfólio

---

## 🧪 Escopo dos Testes

Os testes foram aplicados aos seguintes endpoints do recurso **Posts**:

- `GET /posts`
- `GET /posts/{id}`
- `GET /posts?userId={userId}`
- `POST /posts`
- `PUT /posts/{id}`
- `DELETE /posts/{id}`

---

## ✅ Tipos de Validações Implementadas

- Validação de **status code**
- Validação de **campos obrigatórios**
- Validação de **tipos de dados**
- Validação de **parâmetros de query**
- Validação de **tempo de resposta**
- Cenários **negativos** (IDs inválidos, recursos inexistentes)
- Validação de **contrato da API**

---

## ⚠️ Observações Importantes

A API **JSONPlaceholder** é uma API de simulação (mock):

- Não persiste dados
- Métodos `POST`, `PUT` e `DELETE` retornam sucesso mesmo em cenários inválidos
- Alguns testes negativos validam o **comportamento observado da API**, e não erros reais

Essas limitações foram consideradas na criação dos casos de teste.

---

## 🛠️ Ferramentas Utilizadas

- **Postman**
- **JavaScript**
- **Chai Assertions** (via `pm.expect`)

---

## ⚙️ Configuração do Projeto

- Todas as variáveis (URL base, IDs inválidos, paths) estão definidas **no nível da Collection**
- Não é necessário configurar Environment para execução

---

## ▶️ Como Executar os Testes

1. Importar a **Collection** no Postman
2. Selecionar a Collection
3. Executar manualmente as requisições  
   **ou**
4. Utilizar o **Collection Runner** do Postman

---

## 👤 Autor

**Aquiles Araújo**  
Estudante de Engenharia de Software  
Foco em QA / Testes de Software
