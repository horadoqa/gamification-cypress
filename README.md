# Gamification com Cypress

## 🎮 Ideias de Gamification para aprender Cypress

### 1️⃣ **“Missão QA” (Estilo RPG / Missões)**

**Conceito:**
O jogador é um QA júnior que precisa “salvar” uma aplicação cheia de bugs.

**Como funciona:**

* Cada **fase = um conceito do Cypress**
* O jogador recebe uma missão, ex:

  * 🧪 *“Verifique se o login funciona”*
  * 🧪 *“Garanta que o carrinho adiciona produtos corretamente”*

**Exemplos de fases:**

* Fase 1: `cy.visit`, `cy.get`
* Fase 2: `should`, `contains`
* Fase 3: `fixtures`, `beforeEach`
* Fase 4: `intercept`, mocks de API
* Fase 5: testes flaky / retry

✅ **O jogador só passa de fase se o teste Cypress passar.**

---

### 2️⃣ **“Bug Hunter” (Caça aos Bugs)**

**Conceito:**
O sistema propositalmente tem falhas e testes incompletos.

**Desafio:**

* O jogador recebe um projeto Cypress com testes quebrados
* Precisa **corrigir ou criar testes** para capturar o bug

**Pontuação baseada em:**

* Cobertura de cenários
* Uso correto de comandos Cypress
* Clareza dos testes

Exemplo:

> “O botão funciona visualmente, mas não envia o formulário. Crie um teste que capture isso.”

---

### 3️⃣ **“Desafio Diário Cypress”**

**Conceito:**
Pequenos desafios diários (tipo Duolingo).

**Exemplos de desafios:**

* “Use `cy.intercept` para mockar esta API”
* “Transforme este teste frágil em um teste robusto”
* “Evite `cy.wait(5000)`”

**Gamificação:**

* 🔥 Streak diário
* 🏆 Badges (Interceptor Master, DOM Ninja, etc.)

---

### 4️⃣ **“Escape Room QA”**

**Conceito:**
O jogador está preso em uma aplicação e precisa escrever testes para avançar.

**Exemplo:**

* Porta só abre se:

  * um elemento aparece
  * uma requisição retorna 200
  * um modal fecha corretamente

Cada “porta” é validada por um teste Cypress.

---

### 5️⃣ **Code Golf Cypress**

**Conceito:**
Resolver desafios usando **o menor e mais elegante teste possível**.

Exemplo:

> “Valide este fluxo usando o menor número de linhas sem perder legibilidade.”

Pontuação:

* Menos linhas
* Boas práticas
* Sem anti-patterns (`force: true`, waits fixos, etc.)

---


Drive: https://drive.google.com/drive/folders/1VW_83X15xpEMz0E9GNQaOCP8iWMBHVH5?usp=sharing