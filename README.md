# Trabalho Final de Programação para Dispositivos Móveis 


# WhatsApp Clone 



### <pre> Alunos:                                RGA:</pre>
<pre>
Kleber Meira Lima				        2017.1906.117-3
Robson Pimenta Moura Junior                             2018.1906.033-0
</pre>


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

Teste 1: Usuários tenta fazer login no sistema sem possuir uma conta cadastrada:

![image2](https://user-images.githubusercontent.com/43676289/86009502-4c303380-b9e8-11ea-83c3-c4b249eb3d1a.png)


Teste 2: Usuário cadastrado tenta acessar o sistema digitando uma senha incoerente com a informada no cadastro:

![image6](https://user-images.githubusercontent.com/43676289/86009522-52261480-b9e8-11ea-905a-d25b415fd0aa.png)

Teste 3: Usuário tenta cadastrar uma nova conta com uma e-mail já utilizado anteriormente:

![image5](https://user-images.githubusercontent.com/43676289/86009517-50f4e780-b9e8-11ea-9910-219e8d7f0db4.png)


Teste 4: Usuário tenta cadastrar uma nova conta com uma e-mail inválido:

![image4](https://user-images.githubusercontent.com/43676289/86009516-4fc3ba80-b9e8-11ea-96ed-1ecbd73dd763.png)


Teste 5: Usuário tenta iniciar uma conversa com um e-mail não vinculado a uma conta válida:

![image1](https://user-images.githubusercontent.com/43676289/86009072-bb595800-b9e7-11ea-9a59-e6543a460eb9.png)


Teste 6: Usuário tenta enviar uma mensagem sem conteúdo: 

![image3](https://user-images.githubusercontent.com/43676289/86009510-4e928d80-b9e8-11ea-9286-06c2871e712f.png)
