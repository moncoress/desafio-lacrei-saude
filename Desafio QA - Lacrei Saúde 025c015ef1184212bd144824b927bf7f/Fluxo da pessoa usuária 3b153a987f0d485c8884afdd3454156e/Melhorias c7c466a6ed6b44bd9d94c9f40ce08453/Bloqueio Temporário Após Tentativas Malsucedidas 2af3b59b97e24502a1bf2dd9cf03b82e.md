# Bloqueio Temporário Após Tentativas Malsucedidas

Prezados desenvolvedores da Lacrei Saúde,

Gostaria de sugerir uma melhoria no fluxo de login, visando aumentar a segurança e proteger contra possíveis tentativas de acesso não autorizado.

Atualmente, o sistema permite que os usuários façam várias tentativas de login com dados inválidos sem restrições, o que pode abrir brechas para ataques de força bruta ou tentativas de acesso não autorizado.

Para mitigar esse risco, proponho a seguinte implementação:

Após 6 tentativas de login malsucedidas com dados inválidos (seja com e-mail ou senha incorretos), o sistema irá temporariamente bloquear a conta do usuário por um período de 10 minutos. Durante esse período, qualquer tentativa adicional de login será rejeitada, e o usuário receberá uma notificação em seu e-mail informando sobre o bloqueio temporário, informando qual dado incorreto foi utilizado no último login.

Após o período de bloqueio de 10 minutos, a conta do usuário será automaticamente desbloqueada, permitindo que ele tente logar novamente.

Essa medida visa proteger as contas dos usuários contra possíveis ataques de força bruta ou tentativas de acesso não autorizado, ao mesmo tempo em que minimiza qualquer inconveniente para os usuários legítimos.

Atenciosamente,

Mariana Monçores.

=)