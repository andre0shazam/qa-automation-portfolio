# QA Automation Portfolio — E2E

Projeto de automação de testes de ponta a ponta (E2E) para aplicações web, construído para demonstrar boas práticas de Garantia da Qualidade (QA) e design de testes.

> 🚧 **Status do Projeto:** Em desenvolvimento (Fase 1: Testes de UI concluída).

## 🎯 O que já está implementado
- **Automação de UI:** Teste E2E cobrindo o fluxo de login na aplicação [Sauce Demo](https://www.saucedemo.com), validando a autenticação do usuário e o redirecionamento para a área logada.

## 🛠️ Tecnologias Utilizadas
- **Cypress:** Automação de testes E2E.
- **JavaScript:** Linguagem de programação dos testes.
- **Node.js / npm:** Gerenciamento de dependências.
- **Git / GitHub:** Versionamento e hospedagem.

## 📂 Estrutura do Projeto
```text
qa-automation-portfolio/
├── cypress/
│   ├── e2e/            # Casos de teste (login.cy.js)
│   ├── fixtures/       # Dados estáticos para os testes
│   └── support/        # Comandos customizados e configurações
├── .gitignore          # Arquivos ignorados pelo Git
├── cypress.config.js   # Configurações do Cypress
├── package.json        # Dependências do projeto
└── README.md           # Documentação