# Trabalho Final de Programação para Dispositivos Móveis 


# WhatsApp Clone 



Alunos:                                           RGA:
Kleber Meira Lima				                             2017.1906.117-3
Robson Pimenta Moura Junior                          2018.1906.033-0



## Visão Geral

	O aplicativo criado pelo grupo é inspirado num aplicativo já existente, o WhatsApp. Ou seja, é um aplicativo de comunicação por mensagem, onde uma pessoa pode mandar mensagem a outra e assim iniciar uma conversa.  Porém, diferentemente do WhatsApp, o cadastro é feito via e-mail, outra diferença é que para se iniciar uma conversa o usuário deve saber o e-mail da pessoa a qual ele ou ela deseja se comunicar. O aplicativo só possui um tipo de usuário, ele pode criar uma conta usando um e-mail válido, pode iniciar uma conversa com outro usuário que possua uma conta no app. 


## Requisitos Funcionais do Sistema	

RF1: O sistema deve permitir o cadastro de novos usuários, solicitando os seguintes atributos: nome do usuário, e-mail e senha para acesso.

RF2: O sistema deve permitir o login de usuários já cadastrados, solicitando o seguintes atributos para a verificação com o banco de dados: e-mail e senha previamente cadastrados.

RF3: O sistema deve permitir o adicionamento de um novo contato, solicitando para o usuário o e-mail do novo contato, que deve estar cadastrado no aplicativo.

RF4: O sistema deve permitir inicio de uma conversa com um contato já cadastrado.

RF5: O sistema deve permitir o envio de mensagem para um contato. 

RF6: O sistema deve permitir a pesquisa de uma conversa, solicitando o nome do contato da conversa. 


# Testes de Caixa Preta

Teste 1: Usuários não cadastrados não podem fazer login no sistema:

Teste 2: Usuários cadastrado não podem acessar o sistema, caso a senha não esteja certa:

Teste 3: Usuário tenta cadastrar uma nova conta com uma e-mail já utilizado anteriormente:

Teste 4: Usuário tenta cadastrar uma nova conta com uma e-mail inválido:

Teste 5: Usuário tenta iniciar uma conversa com um e-mail não vinculado a uma conta válida:

Teste 6: Usuário tenta enviar uma mensagem sem conteúdo: 
