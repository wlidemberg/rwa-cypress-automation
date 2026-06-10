# CN-01 - Login com credenciais válidas
**Dado** que o usuário está na tela de login
**Quando** informar um usuário válido
**E** informar uma senha válida
**E** clicar no botão "Entrar"
**Então** o sistema deve autenticar o usuário
**E** direcioná-lo para a página inicial da área autenticada.

# CN-02 - Login com e-mail em formato inválido
**Dado** que o usuário está na tela de login
**Quando** informar um usuário em formato inválido
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-03 - Login com usuário não cadastrado
**Dado** que o usuário está na tela de login
**Quando** informar um usuário não cadastrado no sistema
**E** informar senha qualquer
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-04 - Login com senha incorreta
**Dado** que o usuário está na tela de login
**Quando** informar usuário cadastrado
**E** informar senha incorreta
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-05 - Login sem informar usuário
**Dado** que o usuário está na tela de login
**Quando** não informar usuário
**E** informar uma senha qualquer
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-06 - Login sem informar senha
**Dado** que o usuário está na tela de login
**Quando** informar um usuário válido
**E** não informar senha
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-07 - Login sem informar usuário e senha
**Dado** que o usuário está na tela de login
**Quando** não informar usuário e senha
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro