# CT009 - Senha Fraca

- **Descrição:** Verificar se o sistema exige uma senha forte ao realizar o cadastro.
- **Passos:**
1. Acessar a página de cadastro de usuário.
2. Inserir uma senha inválida, como "mariana" (sem 8 dígitos, caracteres especiais, letra maiúcula e números).
3. Tentar enviar o formulário de cadastro.
- **Resultado Esperado:**
    1. Abaixo do campo de preenchimento de senha, deve ser exibida a mensagem: “A senha deve ter no mínimo 8 caracteres".
    2. No campo de repetir a senha, as mensagens que devem ser exibidas são: “*A senha deve conter, no mínimo: 8 caracteres, Letra maiúscula, Número, Caractere especial(ex: #!*-_&), As senhas devem ser iguais.”*