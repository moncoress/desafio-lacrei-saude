# CT130 - Data de nascimento inválida (melhoria)

- **Objetivo:** Verificar se o sistema permite que eu coloque uma data de nascimento inválida.

- **Pré-Requisito:**
    1. Estar logado na aplicação;
    2. Estar na página "[Informações Pessoais | Lacrei](https://paciente.lacreisaude.com.br/perfil/)”.

- **Passos:**
    1. Acessar o perfil do usuário;
    2. Estar na área de “Informações pessoais”;
    3. Rolar a barra do site até chegar no campo de “Editar Dados";
    4. Alterar a data de nascimento para uma inválida [Ex: 05/09/2025];
    5. Clicar em "Salvar".

- **Resultado Esperado:** A mensagem "Algo deu errado. Por favor, tente novamente.” aparece logo acima do botão de "Salvar".
- Sugestão de Melhoria:
    - Uma mensagem mais específica, como: "Por favor, insira uma data de nascimento válida”
    - Para evitar futuros transtornos, o sistema não deveria permitir que o usuário navegue para o futuro num campo como esse.