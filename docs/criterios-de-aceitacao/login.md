# CA - Feature de Login

## Objetivo
Permitir que usuários previamente cadastrados realizem autenticação no sistema para acessar funcionalidades protegidas.

### CA-LOGIN-001 - Exibição da tela de login
**Dado** que o usuário acessa a tela de login
**Então** o sistema deve exibir
- Logo da aplicação
- Título "Sign In"
- Campo Username
- Campo Password
- Checkbox Remember Me
- Botão SIGN IN
- Link "Don't have an account? Sign Up"
- Footer Built Cypress 

### CA-LOGIN-002 - Obrigatoriedade do Campo Username
**Dado** que o usuário acessa a tela de login
**Quando** deixar o campo Username vazio
**Então** o sistema deve exibir a mensagem: "Username is required"

### CA-LOGIN-003 - Tamanho mínimo da senha
**Dado** que o usuário ecessa a tela de login
**Quando** informar um senha com menos de 4 caracteres
**Então** o sistema deve exibir mensagem: "Password must contain at least 4 characters"

### CA-LOGIN-004 - Habilitação do botão SIGN IN
**Dado** que o usuário acessa a tela de login
**Quando** os campos Username e Password não atenderem os critérios mínimos 
**Então** o botão SIGN IN deve permanecer desabilitado
**E** não permitir a tentiva de autenticação

### CA-LOGIN-005 - Login com sucesso
**Dado** que o usuário acessa a tela de login
**Quando** informar Username e Password válidos
**Então** o sistema deve autenticar o usuário
**E** redireciona-lo para area autenticada

### CA-LOGIN-006 - Login com credenciais inválidas
**Dado** que o usuário acessa a tela de login
**Quando** informar Username e Password inválidos
**Então** o sistema não deve autenticar o usuário
**E** deve exibir a mensagem: "Username or Password is invalid"

### CA-LOGIN-007 - Checkout Remember ME
**Dado** que o usuário acessa a tela de login
**Quando** marcar o checkout "Remember Me"
**Então** o sistema deve salvar credenciais do usuário no dispositivo.


### CA-LOGIN-008 - Navegação para cadastro
**Dado** que o usuário acessa a tela de login
**Quando** clicar no link: "Don't have an account: Sign Up"
**Então** o sistema deve redireciona-lo para a tela de cadastro

## Observações Identificadas Durante a Exploração
As observações abaixo representam comportamentos identificados durante os testes exploratórios e ainda precisam ser avaliadas quanto a regra de negócio esperado:

### OBS-LOGIN-001
O campo Username aceita espaços em branco como entrada válida para habilitação do botão SIGN IN.

### OBS-LOGIN-002
O campo Password aceita espaços em branco como caracteres válidos pra validação do tamanho mínimo

### OBS-LOGIN-003
Não foi identificado limite máximo de caracteres para os campos Username e Password na interface.