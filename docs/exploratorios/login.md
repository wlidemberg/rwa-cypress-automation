# Sessão Exploratória - Login

## Objetivo
Identificar comportamentos, validações, regras de negocios e oportunidades de melhoria da funcionalidade de Login do Real World App.

## Ambiente
- Aplicação: Real World App (RWA)
- URL: http://localhost:3000/signin
- Navegador: Google Chrome
- Data: 09/06/2026

## Regras identificadas:

### RN-01
O campo username é obrigatório.
Mensagem apresentada:
*Username is required*

### RN-02
O campo password é obrigatório e deve ter no minímo 4 caracteres
Mensagem apresentada:
*Password must contain at least 4 characters* (a senha deve conter pelo menos 4 caracteres)

### RN-03
O botão "SIGN IN" permanece desabilitado enquanto Username e Password não atenderem os critérios mínimos de preenchimento.

### RN-04
Ao informar credenciais inválidas, o sistema exibe mensagem:
*Username or password is invalid* (O nome de usuário ou a senha são inválidos)

## Componentes identificados na tela
- Logo da aplicação;
- Título Sign In;
- Campo Username;
- Campo Password;
- Checkbox Remember Me;
- Botão SIGN IN;
- Link Sign Up
- Footer Built by Cypress

## Novas descobertas

### OBS-01
O campo Username considera espaços em branco como valor válido para habilitação do botão Sign In

### OBS-02
O campo Password considera espaços em branco como caracteres válidos para a validação do tamanho mínimo.

### OBS-03
A presença de um unico espaço em branco no campo Username é suficiente para que o sistema considere o campo preenchido.

### OBS-04
Não foi identificado limite de tamanho para o campo Username

### OBS-05
Não foi identificado limite de tamnho para o campo Password

### OBS-06
Nenhuma mensagem relacionada ao tamanho máximo dos campos foi apresentada.