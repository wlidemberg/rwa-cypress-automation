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
O sistema cadastrou o usuário e redirecionou para a teka de Login

### Evidência:
https://www.awesomescreenshot.com/video/53664528?key=fc870654dae918f9b645f98921d03711

### Status:
Passou


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
Sistema exibiu mensagem "First Name is required" e mantece o bptão Sign Up desabilitado

### Evidência:
[Execução do teste](https://www.awesomescreenshot.com/video/53664630?key=3321299e1c992a47ccee3363cebc21d1)

### Status:
Passou


## CT-REGISTER-03
### Título:
Cadastro sem preencher Last Name

### Objetivo:
Validar que o sistema impede o cadastro quando o campo Last Name não é preenchido

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
O sistema não habilitou o botão Sign Up quando o campo Last Name permaneceu vazio. A mensagem "Last Name is required" foi exibida após o campo receber foco e perder foco.

### Evidência:
[Execução do teste](https://www.awesomescreenshot.com/video/53664710?key=07c11ce057c694357f0516facb19dce1)

### Status:
Passou

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
O sistema exibiu a mensagem "Username is required" e manteve o botão Sign Up desabilitado 

### Evidência:
[Execução dos testes](https://www.awesomescreenshot.com/video/53664963?key=30c6e71d538f068c76ed0c748b8fc121)

### Status:
Passou


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
O sistema exibiu a mensagem "Enter your password" e mateve o botão Sign Up desabilitado

### Evidência:
[Execução dos Testes](https://www.awesomescreenshot.com/video/53665011?key=313125eb12df32f3afe9ab216663dd3b)

### Status:
Passou

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
O sistema exibiu a mensagem "Confirm your password" e manteve o botão Sign Up desabilitado

### Evidência:
[Execução dos testes](https://www.awesomescreenshot.com/video/53665053?key=5b43121132e75531933fb3919b70e1e4)

### Status
Passou

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
O sistema de exibir mensagem "Password must contain at least 4 characters" e manter botão Sign Up desabilitado

### Resultado obtido:
o sistema exibiu a mensagem "Password must contain at least 4 charecters" e manteve o botão Sign Up desabilitado

### Evidência:
[Execução dos testes](https://www.awesomescreenshot.com/video/53665088?key=9b6eb33927e4243d6df023668a98c5d2)

### Status:
Passou


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
O sistem deve exibir mensagem "Password does not match" e manter o botão Sign Up desabilitado    

### Resultado obtido:
O sistema exibiu a mensagem "password does not match" e manteve o botão Sign Up desabilitado

### Evidência:
[Execução dos teste](https://www.awesomescreenshot.com/video/53665163?key=8b065995dea2352015d8f62e5c437b38)

### Status
Passou

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
o sistema não criou novo usuário com username existente

### Evidência:
[Execução dos teste](https://www.awesomescreenshot.com/video/53665234?key=121b8702c598b76769af58fa6530f2a9)

### Status
Passei