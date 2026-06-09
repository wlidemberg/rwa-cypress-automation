# CN-01 - Login com credenciais válidas
**Dado** que o usuário está na tela de login
**Quando** informar um e-mail válido
**E** informar uma senha válida
**E** clicar no botão "Entrar"
**Então** o sistema deve autenticar o usuário
**E** direcioná-lo para a página inicial da área autenticada.

# CN-02 - Login com e-mail em formato inválido
**Dado** que o usuário está na tela de login
**Quando** informar um e-mail em formato inválido
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-03 - Login com e-mail não cadastrado
**Dado** que o usuário está na tela de login
**Quando** informar um e-mail não cadastrado no sistema
**E** informar senha qualquer
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-04 - Login com senha incorreta
**Dado** que o usuário está na tela de login
**Quando** informar e-mail cadastrado
**E** informar senha incorreta
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-05 - Login sem informar e-mail
**Dado** que o usuário está na tela de login
**Quando** não informar e-mail
**E** informar uma senha qualquer
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-06 - Login sem informar senha
**Dado** que o usuário está na tela de login
**Quando** informar um e-mail válido
**E** não informar senha
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro

# CN-07 - Login sem informar e-mail e senha
**Dado** que o usuário está na tela de login
**Quando** não informar e-mail e senha
**E** clicar no botão "Entrar"
**Então** o sistema não deve autenticar o usuário
**E** deve exibir mensagem de erro