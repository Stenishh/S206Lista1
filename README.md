Este projeto contém testes automatizados para o site Para Bank, que simula operações de um banco online. Os testes foram escritos usando o framework Cypress e cobrem cenários como registro de novo usuário, login, logout, transações, atualização de perfil e testes com credenciais inválidas.
Testes Incluídos
Registro de Novo Usuário:

Simula o registro de um novo usuário no site usando um ID e Senha dinâmicos baseados no horário atual.
Verifica se o registro foi realizado com sucesso.
Teste de Login:

Realiza login no site com o usuário registrado anteriormente.
Verifica se o usuário foi autenticado com sucesso e a página de "Overview" de contas é exibida.
Teste de Logout:

Realiza o logout do usuário e verifica se a página de login é exibida corretamente.
Teste de Transação:

Simula uma transferência de $1000 para outra conta e verifica o sucesso da operação.
Atualização de Perfil:

Atualiza as informações de contato do usuário registrado e verifica se os dados foram atualizados corretamente.
Teste com Credenciais Inválidas:

Tenta realizar login com um nome de usuário e senha incorretos e verifica se a mensagem de erro apropriada é exibida.
