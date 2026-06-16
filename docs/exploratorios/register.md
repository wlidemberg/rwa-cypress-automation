# Sessão Exploratória - Cadastro de Usuário

## Objetivo
Identificar comportamentos, validações, regras de negocio e oportunidades de melhoria da funcionalidade de Cadastro de Usuário do Real World APP.

## Ambiente
- Aplicação Real World APP (RWA)
- URL: http://localhost:3000/signup
- Navegador: Google Chrome
- Data: 15/06/2026

## Regras Identificadas:

### RN-01
O campo First Name é obrigatório.
Mensagem apresentada:
*First Name is required*

### RN-02
O campo Last Name é obrigatório
Mensagem apresentada:
*Last Name is required*

### RN-03
O campo Username é obrigatório
Mensagem apresentada:
*User Name is required*

### RN-04
O campo Password é obrigatório
Mensagem apresentada:
*Enter your password*

### RN-05
O campo Confirm Password é obrigatório
Mensagem apresentada:
*Confirm your password*

### RN-06
O campo Password deve conter no mínimo 4 caracteres
Mensagem apresentada:
*Password must contain at least 4 characters*

### RN-07
O campo Confirm Password deve conter o mesmo vamor informado no campo Password
Mensagem apresentada:
*Password does not match*

### RN-08
O botão Sign in deve permanecer desabilitado enquanto existirem campos obrigatórios não preenchidos ou inválidos
Comportamento Observado:
*O botão só é habilitado quando todos os campos obrigatórios são preenchidos e atedem as validações*

### RN-09
Não é permitido cadastrar um Username já existente no sistema
Comportamento observado:
*O sistema não realiza o cadastro de usuários com Username já cadastrado*

### RN-10
Após o cadastro realizada com sucesso, o sistema redireciona o usuário para a tela de login
Comportamento observado:
*Redirecionamento para a página Sign In*

### RN-11
Os campos First Name e Last Name aceitam espaços em branco como entrada válida para habilitação do botão Sign Up

Observação:
*Comportamento identificado durante os testes exploratórios. Pode representar falha na validação*

### RN-12
Os campos First Name, Last Name, Username, Password e Confirm Password não possuem limite máximo de caracters
Observação:
*Não foi identificada restrição durante os testes exploratórios*

### RN-13
Os campos aceitam espaços em branco no inicio e no final dos valores informados
Observação:
*O sistema não apresenta mensagem de validação*