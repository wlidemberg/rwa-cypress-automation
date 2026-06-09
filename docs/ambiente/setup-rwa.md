# Setup do Ambiente Real World App (RWA)

## Objetivo

Documentar o processo de instalação e execução do Real World App (RWA), aplicação utilizada como sistema sob teste para os exercícios de automação com Cypress.

---

## Sobre o Projeto

O Real World App (RWA) é uma aplicação open source desenvolvida pela equipe do Cypress para demonstrar estratégias de testes automatizados em um ambiente real.

A aplicação simula uma plataforma de transações financeiras entre usuários, permitindo funcionalidades como:

* Cadastro de usuários
* Login
* Transferência de dinheiro
* Solicitação de pagamentos
* Gerenciamento de contas bancárias
* Histórico de transações

---

## Pré-requisitos

### Node.js

Versão compatível:

```text
^20.0.0 || ^22.0.0 || ^24.0.0
```

Versão utilizada neste projeto:

```text
v22.14.0
```

### NPM

Versão utilizada:

```text
11.14.1
```

### Yarn

Versão utilizada:

```text
1.22.22
```

### Git

Necessário para clonar o repositório oficial.

---

## Clonando o Projeto

Executar:

```bash
git clone https://github.com/cypress-io/cypress-realworld-app.git
```

Entrar na pasta do projeto:

```bash
cd cypress-realworld-app
```

---

## Instalação das Dependências

Executar:

```bash
yarn install
```

A instalação pode levar alguns minutos dependendo da conexão e do desempenho da máquina.

---

## Execução da Aplicação

Executar:

```bash
yarn dev
```

Após a inicialização, a aplicação estará disponível em:

```text
http://localhost:3000
```

Tela de Login:

```text
http://localhost:3000/signin
```

---

## Resultado da Instalação

Ambiente configurado com sucesso.

Validações realizadas:

* Aplicação iniciada corretamente
* Tela de login acessível
* Dependências instaladas sem erros
* Ambiente pronto para exploração funcional
* Ambiente pronto para automação de testes com Cypress

---

## Próximos Passos

* Exploração da funcionalidade de Login
* Levantamento de regras de negócio
* Refinamento dos cenários de teste
* Refinamento dos casos de teste
* Implementação da automação com Cypress
* Integração contínua com GitHub Actions
* Geração de relatórios de execução
