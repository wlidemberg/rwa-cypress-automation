# Cenários de Teste Feature de Cadastro de Usuário

### CN-01 - Cadastro realizado com sucesso
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher todos os campos obrigatórios com dados válidos
**E** clicar no botão Sign Up
**Então** o sistema deve realizar o cadastro
**E** redireciona-lo para a tela de Login

### CN-02 - Cadastro sem preencher First Name
**Dado** que o usuário esteja na tela de cadastro
**Quando** não preencher o campo First Name
**Então** o sistema deve exibir mensagem: "First Name is required"
**E** manter o botão Sign Up desabilitado

### CN-03 - Cadastro sem preencher Last Name
**Dado** que o usuário esteja na tela de cadastro
**Quando** não preencher o campo Last Name
**Então** o sistema deve exibir mensagem "Last Nama is required"
**E** mater o botão Sign Up desabilitado

### CN-04 - Cadastro sem preencher Username
**Dado** que o usuário esteja na tela de cadastro
**Quando** não preencher o campo Username
**Então** o sistema deve exibir mensagem "Username is required"
**E** manter o botão Sign Up desabilitado

### CN-05 - Cadastro sem preencher Password
**Dado** que o usuário esteja na tela de cadastro
**Quando** não preencher o campo Password
**Então** o sistema deve exibir mensagem "Enter your password"
**E** manter o botão Sign Up desabilitado

### CN-06 - Cadastro sem preencher Confirm Password
**Dado** que o usuário esteja na tela de cadastro
**Quando** não preencher o campo Confirm Password
**Então** o sistema deve exibir mensagem "Confirm your password"
**E** manter o botão Sign Up desabilitado

### CN-07 - Cadastro com Password menor 4 caracteres
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher o campo Password com menos de 4 caracteres
**Então** o sistema deve exibir mensagem "Password must contain at least 4 characters"
**E** impedir a conclusão do cadastro

### CN-08 - Cadastro com Confirm Password diferente de Password
**Dado** que o usuário esteja na tela de cadastro
**Quando** preencher o campo Confirm Password diferente de Password
**Entao** o sistema deve exibir mensagem "Password does not match"
**E** impedir a conclusão do cadastro

### CN-09 - Cadastro com Username existente
**Dado** que o usuário esteja na tela de cadastro
**Quando** tentar realizar novo cadastro utilizando username existente
**Então** o sistema não deve criar novo usuário