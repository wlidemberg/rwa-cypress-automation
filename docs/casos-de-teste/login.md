# CT-LOGIN-001

## Título
Login com sucesso

## Objetivo:
Validar que um usuário cadastrado consegue acessar o sistema utilizando credenciais válidas

## Pré-condições:
- Usuário previamente cadastrado
- Sistema disponível

## Massa de dados:
- Usuário válido
- Senha válida

## Passos:
1. Acessar página de login
2. Informar usuário válido
3. Informa senha válida
4. Clicar no botão "Entrar"

## Resultado esperado:
O usuário deve ser autenticado e direcionado para área logada

## Resultado obtido:
O usuário foi atenticado com sucesso e redirecionado para a página inicial da área autenicada.

## Evidência:
https://www.awesomescreenshot.com/video/53616051?key=bfd2e972dc30d8771df34f9d928d3fc5

## Status:
Passou

# CT-LOGIN-002
## Título:
Login com usuário não cadastrado

## Objetivo:
Validar que o sistema impede a autenticação quando um usuário não cadastrado tenta realizar login.

## Pré-condição:
- Sistema disponível

## Massa de dados:
- Usuário não cadastrado no sistema (teste_username)
- Senha válida (123456)

## Passos:
1. Acessar página de login
2. Informar usuário não cadastrado no sistema
3. Informar senha
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem "Username or Password is invalid" e impedir o acesso do usuário

## Resultado obtido:
O sistema impediu a autenticação do usuário e exibiu mensagem "Username or Password is invalid"

## Evidência:
https://www.awesomescreenshot.com/video/53616749?key=1ab13dc06636c026f046977c102c752f

## Status:
Passou

# CT-LOGIN-003
## Título:
Login com senha incorreta

## Objetivo:
Validar se o sistema bloqueia o acesso e exibe mensagem correta ao informar um senha incorreta ao usuário cadastrado no sistema

## Pré-condição:
- Sistema disponível
- Usuário cadastrado no sistema

## Massa de Dados:
- Informar usuário cadastrado (berg_sousa)
- Informar senha incorreta ao usuário cadastrado (12345678)

## Passos:
1. Acessar página de login
2. Informar usuário cadastrado válido
3. Informar senha incorreta a cadastrada no sistema
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem "Username or Password is invalid" e impedir o acesso do usuário

## Resultado obtido:
O sistema impediu a autenticação do usuário e exibiu mensagem "Username or Password is invalid"
## Evidência:
https://www.awesomescreenshot.com/video/53617005?key=6e5f1ef11e33a26403d76de93b18e187

## Status:
Passou


# CT-LOGIN-004
## Título:
Login sem informar usuário

## Objetivo:
Validar se o sistema bloqueia o acesso e exibe mensagem correta ao deixar o campo de usuário em branco

## Pré-condição:
- Sistema disponível

## Massa de dados:
- Senha (123456)

## Passos:
1. Acessar página de login
2. Não informar nada no usuário
3. Informar uma senha qualquer
4. Verificar comportamento da tela

## Resultado esperado:
O sistema deve exibir mensagem "Username is required" e não habilitar o botão SIGN IN

## Resultado obtido:
O sistema não habilitou o botão SIGN IN e exibiu mensagem "Username is required"

## Evidência:
https://www.awesomescreenshot.com/video/53617156?key=47ed5b45a8c8a496d0e3b0e14ff979ea

## Status:
Passou

# CT-LOGIN-005
## Título:
Login sem informar senha

## Objetivo:
Validar se o sistema bloqueia acesso e exibe mensagem correta ao deixar o campo de senha em branco

## Pré-condição:
- Sistema disponível
- Usuário cadastrado no sistema

## Massa de Dados:
- Usuário cadastrado no sistema (berg_sousa)

## Passos:
1. Acessar página de login
2. Informar usuário cadastrado e válido
3. Não informar senha
4. Verificar comportamento da tela

## Resultado esperado:
O sistema deve manter botão SIGN IN desabilitado

## Resultado obtido:
O sistema manteve o botão SIGN IN desabilitado
## Evidência:
https://www.awesomescreenshot.com/video/53617341?key=ffcf004a62d00427b4e82b130bd03546

## Status:
Passou

# CT-LOGIN-006
## Título:
Login sem informar usuário e senha

## Objetivo:
Validar se o sistema bloqueia acesso e exibe mensagem correta ao deixar usuário e senha em branco

## Pré-condição:
- Sistema disponível

## Massa de Dados:


## Passos:
1. Acessar página de login
2. Não infomar usuário
3. Não informar senha
4. Verificar comportamento de tela

## Resultado encontrado:
O sistema deve exibir mensagem "Username is required" e manter o botão SIGN IN desabilitado

## Resultado obtido:
O sistema exibiu mensagem "Username is required" e manteve o botão SIGN IN desabilitado

## Evidência:
https://www.awesomescreenshot.com/video/53617451?key=d996b4424864f2caceb07bed68b3b82e

## Status:
Passou