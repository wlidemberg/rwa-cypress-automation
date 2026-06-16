# Critérios de Aceitação Feature Cadastro de Usuários

## Objetivo
Permitir que usuários possam se cadastrar no sistema e criar contas de usuários para acessar funcionalidades protegidas.

### CA-01 - Cadastro realizado com sucesso
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher todos os campos obrigatórios com dados válidos
**E** clicar no botão Sign Up
**Então** o sistema deve realizar cadastro do usuário
**E** redireciona-lo para a tela de login

### CA-02 - Campos Obrigatórios
**Dado** que o usuário estela na tela de cadastro
**Quando** deixar um ou mais campos obrigatórios em branco
**Então** o sistema deve exibir mensagem de validação correspondente
**E** manter o botão Sign Up desabilitado
Campos Obrigatórios:
- First Name
- Last Name
- Username
- Password
- Confirm Password

### CA-03 - Senha com menos de 4 caracteres
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher campo password com menos de 4 caracteres
**Então** o sistema deve exibir mensagem "Password must contain at least 4 characters"
**E** impedir a conclusão do cadastro

### CA-04 - Confirmação de senha diferente
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher o campo Confirm Password com valor diferente de Password
**Então** o sistema deve exibir mensagem "Password does not match"
**E** impedir a conclusão do cadastro

### CA-05 - Username já existente
**Dado** que o usuário esteja na tela de cadastro
**Quando** quando tentar realizar novo cadastro com username já existente no sistema
**Então** o sistema não deve criar novo usuario

### CA-06 - Habilitação do botão Sign Up
**Dado** que o usuário esteja na tela de cadastro
**Quando** todos os campos obrigatórios forem preenchidos com dados válidos
**Então** o botão Sign Up deve ser habilitado para envio do formulário

### CA-07 - Navegação para login
**Dado** que o usuário esteja na tela de cadastro
**Quando** clicar no link Have an account? Sign In
**Então** o sistema deve redireciona-lo para a tela de login
