# CT-LOGIN-001

## Título
Login com sucesso

## Objetivo:
Validar que um usuário cadastrado consegue acessar o sistema utilizando credenciais válidas

## Pré-condições:
- Usuário previamente cadastrado
- Sistema disponível

## Massa de dados:
- E-mail válido
- Senha válida

## Passos:
1. Acessar página de login
2. Informar e-mail válido
3. Informa senha válida
4. Clicar no botão "Entrar"

## Resultado esperado:
O usuário deve ser autenticado e direcionado para área logada

## Resultado obtido:
Não executado

## Status:
Não executado

# CT-LOGIN-002
## Título:
Login com e-mail em formato inválidas

## Objetivo:
Validar se o sistema bloqueia o acesso e exibe mensagem correta quando é informado e-mail com formato inválido.

## Pré-condições:
- Sistema disponível

## Massa de dados:
- E-mail com formato inválido (ex: email.email.com)

## Passos:
1. Acessar página de login
2. informar e-mail com formato inválido
3. informar qualquer senha
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem de erro "E-mail não possui um formato válido" e impedir o acesso do usuário.

## Resultado obtido:
Não executado

## Status:
Não executado

# CT-LOGIN-003
## Título:
Login com e-mail não cadastrado

## Objetivo:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Pré-condição:
- Sistema disponível

## Massa de dados:
- E-mail não cadastrado no sistema

## Passos:
1. Acessar página de login
2. Informar e-mail não cadastrado no sistema
3. Informar senha
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Resultado obtido:
Não Executado

## Status:
Não Executado

# CT-LOGIN-004
## Título:
Login com senha incorreta

## Objetivo:
Validar se o sistema bloqueia o acesso e exibe mensagem correta ao informar um senha incorreta ao e-mail cadastrado no sistema

## Pré-condição:
- Sistema disponível
- Usuário cadastrado no sistema

## Massa de Dados:
- Informar e-mail cadastrado
- Informar senha incorreta ao e-mail cadastrado

## Passos:
1. Acessar página de login
2. Informar email cadastrado válido
3. Informar senha incorreta a cadastrada no sistema
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Resultado obtido:
Não executado

## Status:
Não executado

# CT-LOGIN-005
## Título:
Login sem informar e-mail

## Objetivo:
Validar se o sistema bloqueia o acesso e exibe mensagem correta ao deixar o campo de e-mail em branco

## Pré-condição:
- Sistema disponível

## Massa de dados:
- Senha

## Passos:
1. Acessar página de login
2. Não informar nada no e-mail
3. Informar uma senha qualquer
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Resultado obtido:
Não executado

## Status:
Não executado

# CT-LOGIN-006
## Título:
Login sem informar senha

## Objetivo:
Validar se o sistema bloqueia acesso e exibe mensagem correta ao deixar o campo de senha em branco

## Pré-condição:
- Sistema disponível
- Usuário cadastrado no sistema

## Massa de Dados:
- Informar e-mail cadastrado no sistema

## Passos:
1. Acessar página de login
2. Informar e-mail cadastrado e válido
3. Não informar senha
4. Clicar no botão "Entrar"

## Resultado esperado:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Resultado obtido:
Não executado

## Status:
Não executado

# CT-LOGIN-007
## Título:
Login sem informar e-mail e senha

## Objetivo:
Validar se o sistema bloqueia acesso e exibe mensagem correta ao deixar e-mail e senha em branco

## Pré-condição:
- Sistema disponível

## Massa de Dados:


## Passos:
1. Acessar página de login
2. Não infomar e-mail
3. Não informar senha
4. Clicar no botão "Entrar"

## Resultado encontrado:
O sistema deve exibir mensagem de validação correspondente e impedir o acesso do usuário

## Resultado obtido:
Não executado

## Status:
Não executado