# Casos de Teste Feature de Cadastro de Usuário

## CT-REGISTER-01
### Título:
Cadastro de usuário com sucesso

### Objetivo:
Validar que um visitante consigue criar um conta com dados válidos

### Pré-condição:
- Sistema disponível
- Username não cadastrado

### Massa de dados:
- First Name válido
- Last Name válido
- Username válido e disponível
- Password válida
- Confirm Password igual à Password

### Passos
1. Acessar página de cadastro
2. Preencher o campo First Name
3. Preencher o campo Last Name
4. Preencher o campo Username disponível
5. Prrencher o campo Password válido
6. Preencher o campo Confirm Password igual à Password
7. Clicar no botão Sign Up

### Resultado esperado
O sistema deve cadastrar o usuário e redireciona-lo para a tela de Login

### Resultado obtido
Não Executado

### Evidência:


### Status:
Não Executado

## CT-REGISTER-02
### Título:
Cadastro sem preencher First Name

### Objetivo:
Validar que o sistema impede o cadastro quendo o campo First Name não é preenchido 

### Pré-condição:
- Sistema disponível

### Massa de dados:
- Last Name válido
- Username válido e disponível
- Password válido
- Confirm Password válida

### Passos:
1. Acessar a página de cadastro
2. Não preencher o First Name
3. Preencher os demais campos obrigatórios
4. Verificar o comportamento da tela

### Resultado esperado:
O sistema deve exibir mensagem "First Name is required" e manter o botão Sign Up desabilitado

### Resultado obtido
Não Executado

### Evidência:
Não Executado

### Status:
Não Executado

## CT-REGISTER-03
### Título:
Cadastro sem preencher Last Name

### Objetivo:
Validar que o sistema inpede o cadastro quando o campo Last Name não é preenchido

### Pré-condição:
- Sistema Disponivel

### Massa de dados:
- First Name válido
- Username válido e disponível
- Password válido
- Confirm Password

### Passos:
1. Acessa a página de cadastro
2. Preencher o campo First Name
3. Não preencher o campo Last Name
4. Preencher os demais campos obrigatórios
5. Verificar comportamento na tela

### Resultado esperado:
O sistema deve exibir mensagem "Last Name is required" e manter o botão Sign Up desabilitado

### Resultado obtido:
Não Executado

### Evidência:
Não Executado

### Status:
Não Executado

## CT-REGISTER-04
### Título:
Cadastro sem preencher Username

### Objetivo:
Validar se o sistema impede o cadastro quando o campo Username não é preenchido

### Pré-condição:
- Sistema disponível

### Massa de dados:
- First Name válido
- Last Name válido
- Password válido
- Confirm Password válido

### Passos:
1. Acessar a página de cadastro
2. Preencher o campo  First Name
3. Preencher o campo Last Name
4. Não preencher o campo Username
5. Preencher os demais campos obrigatórios
6. Verificar comportamento da tela

### Resultado esperado:
O sistema deve exibir mensagem "Username is required" e manter o botão Sign Uo desabilitado

### Resultado Obtido:
Não Executado

### Evidência:
Não Executado

### Status:
Não Executado

## CT-REGISTER-05
### Título:
Cadastro sem preencher Password

### Objetivo:
Validar se o sistema impede o cadastro quando o campo Password não é preenchido

### Pré-condição:
- Sistema disponível

### Massa de dados:
- First Name válido
- Last Name válido
- Username válido e disponível
- Confirm Password válido

### Passos:
1. Acessar a página de cadastro
2. Preencher o campo First Name
3. Preencher o campo Last Name
4. Preencher o campo Username
5. Não preencher o campo Password
6. Preencher o campo Confirm Password
7. Verificar comportamento da tela

### Resultado esperado:
O sistema deve exibir mensagem "Enter your password" e manter botão Sign Up desabilitado

### Resusltado obtido:
Não Executado

### Evidência:
Não Executado

### Status:
Não Executado

## CT-REGISTER-06
### Título:
Cadastro sem preencher Confirm Password

### Objetivo:
Validar se o sistema impede cadastro quando o campo Confirm Password não é preenchido

### Pré-condição:
- Sistema disponível

### Massa de dados:
- First Name válido
- Last Name válido
- Username válido e disponível
- Password válido

### Passos:
1. Acessar a página de cadastro
2. Preencher todos os campos obrigátorio
3. Não preencher campo Confirm Password
4. Verificar comportamento da tela

### Resultado esperado:
O sistema deve exibir mensagem "Confirm your password" e manter o botão Sign Up desabilitado

### Resultado obtido:
Não Executado

### Evidência:
Não Executado

### Status
Não Executado


## CT-REGISTER-07
### Título:
Cadastro com Password com menos de 4 caracteres

### Objetivo:
Validar se o sistema impede o cadastro quando o campo password é preenchido com menmos de 4 caracteres

### Pré-condição:
- Sistema disponível

### Massa de dados:
- First Name válido
- Last Name válido
- Username válido
- Password com meno de 4 caracteres

### Passos:
1. Acessar a página de cadastro
2. Preencher todos os campos obrigatórios
3. Preencher campo Password com menos de 4 caracteres
4. Verificar comportamento do sistema

### Resultado esperado:
O sistema de exibir mensagem "Password must contain at least 4 characters"

### Resultado obtido:
Não Executado

### Evidência:
Não Executado

### Status:
Não Executado


## CT-REGISTER-08
### Título:
Cadastro com Confirm Password diferente de Password

### Objetivos:
Validar se o sistema impede o cadastro quando o campo Confirm Password é preenchido diferente de Password

### Pré-condições:
- Sistema disponível

### Massa de dados:
- First Name válido
- Last Name válido
- Username válido
- Password válido
- Confirm Password diferente de Password

### Passos:
1. Acessar a página de cadastro
2. Preencher todos os campos obrigatórios
3. Preencher o campo Confirm Password diferente do Password
4. Verificar comportamento da tela

### Resultado esperado:
O sistem deve exibir mensagem "Confirm does not match"

### Resultado obtido:
Não Executado

### Evidência:
Não Executado

### Status
Não Executado

## CT-REGISTER-09
### Título:
Cadastro com username existente

### Objetivo:
Validar se o sistema impede o cadastro de um novo usuário quando username está cadastrado 

### Pré-condição:
- Sistema disponível
- Username cadastrado

### Massa de dados:
- Fisrt Name válido
- Last Name válido
- Username válido não disponível
- Password válido
- Confirm Password válido

### Passos:
1. Acessar a página de cadastro
2. Preencher todos os campos obrigatórios
3. Preencher Username já cadastrado
4. Verificar comportamento da tela

### Resultado esperado:
O sistema não deve criar novo usuário utilizando username já existente

### Resultado obtido:
Não Executado

### Evidência:
Não Executado

### Status
Não Executado