# QTS-Bruno
Repositório para atividades de QTS no 3 Bimestre

-=Safe Hacking=-
-
	-Página Inicial e página de créditos, página inicial deve apresentar informações sobre o conteúdo do site, meios de reportar problemas, botões onde será possível mudar para a página de “créditos” e página de “login”; página de créditos deve apresentar informações sobre os criadores, contato, meios de reportar problemas e botões onde será possível mudar para a página “inicial” e página de “login”:


	Narrativa:
	- Como botão de “créditos”, "página inicial” ou “Login”
	- Eu quero mudança para a página respectivamente
	- Assim que clicar no botão respectivo
________________________________________

	- Narrativa:
	- Como Login
	- Eu quero entrar com a conta
	- Assim deverá ser enviado para a página principal quando finalizado
 
- Cenário 1: Cliente com dados já cadastrado e com dados corretos
- Dado que deseja logar na sua conta
- E informou Email
- E informou Senha
- Quando entrar com essas informações no login
- Então deve-se conectar à conta
- E ser redirecionado para página principal

- Cenário 2: Cliente com dados já cadastrado e com dados incorretos
- Dado que deseja logar na sua conta
- E informou Email incorreta
- E/ou informou Senha incorreta
- Quando entrar com essas informações no login
- Então deve-se notificar “Email ou Senha incorretos”
- E limpar as caixas de texto
________________________________________

Narrativa:
-
	- Como Cadastro
	- Eu quero criar uma conta
	- Assim deverá ser enviado para a página de Usuário quando finalizado

- Cenário 1: Cliente com dados corretos
- Dado que deseja criar uma conta
- E informou Nome
- E informou Email
- E informou Senha
- E confirmou Senha
- Quando entrar com essas informações no cadastro
- Então deve-se criar à conta
- E ser redirecionado para página de Usuário

- Cenário 2: Cliente com dados incorretos

- Dado que deseja criar uma conta
- E informou Nome 
- E informou Email inexistente
- E informou Senha 
- E/ou confirmou Senha errado
- Quando entrar com essas informações no cadastro
- E Email for inexistente
- Então deve-se notificar “Email inexistente”
- Ou quando Confirmou Senha for diferente de Senha
- Então deve-se notificar “Os dados de Confirmar Senha está diferente da Senha”
