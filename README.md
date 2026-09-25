# -Projeto-Pr-tico-de-QA-APIs-Banco-de-Dados-e-Automa-o-E2E
# 🎯 Projeto Prático de QA: APIs, Banco de Dados e Automação E2E

Bem-vindo(a) ao meu portfólio de Quality Assurance! Este repositório contém a resolução de um desafio prático focado na validação de qualidade em três frentes essenciais do desenvolvimento de software: Testes de API, Consultas SQL e Automação Web.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Postman:** Para testes manuais de API e validação de status codes.
* **SQL (W3Schools):** Para consultas e validação de integridade de dados.
* **Cypress & Node.js:** Para automação de testes End-to-End (E2E) em aplicações Web.

---

## 🚀 Resumo das Atividades Realizadas

### Parte 1: Testes de API (Postman)
Nesta etapa, testei duas APIs públicas (`JSONPlaceholder` e `ReqRes`) para validar cenários de sucesso e erro.
* **Cenário de Sucesso (POST):** Envio de dados válidos para criação de um utilizador. Validação do Status Code `201 Created` e do ID gerado automaticamente pelo sistema.
* **Cenário de Erro (POST):** Simulação de um pedido sem a palavra-passe obrigatória. Validação do Status Code `400 Bad Request` e da mensagem de erro `"Missing password"`.

*(Adiciona aqui a tua imagem do Postman: `![Teste Postman](01_Tarefa3_Postman_Criacao201.png)`)*

### Parte 2: Validação em Banco de Dados (SQL)
Prática de comandos estruturados para validar o comportamento dos dados no back-end, garantindo que os filtros da interface gráfica refletem a realidade do banco de dados.
* Utilização de `SELECT`, `WHERE` e `ORDER BY` para filtrar e ordenar clientes.
* Utilização de `COUNT` e `GROUP BY` para agregação de dados e identificação de potenciais registos duplicados no sistema.

*(Adiciona aqui a tua imagem do SQL: `![Consulta SQL](05_Tarefa7_SQL_GroupBy.png)`)*

### Parte 3: Automação Web E2E (Cypress)
Configuração do ambiente do zero e criação do meu primeiro script de automação para testar um fluxo de autenticação real.
* Acesso ao site `the-internet.herokuapp.com/login`.
* Mapeamento de elementos (`#username`, `#password`, botão de submit).
* Inserção automática de credenciais e validação da mensagem de sucesso (`You logged into a secure area!`).

*(Adiciona aqui a tua imagem do Cypress: `![Automação Cypress](06_Tarefa8_Cypress_Login.png)`)*

---

## ⚙️ Como executar o teste automatizado (Cypress) na sua máquina

Se quiser clonar este repositório e correr o teste localmente, siga os passos:

1. Certifique-se de que tem o [Node.js](https://nodejs.org/) instalado.
2. Clone este repositório e abra o terminal na pasta do projeto.
3. Instale as dependências executando:
   ```bash
   npm install
