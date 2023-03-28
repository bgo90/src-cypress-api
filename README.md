# src-cypress-api
Projeto baseado em Cypress na IDE desenvolvimento VSCode utilizando a linguagem de programação Java.

Prova técnica de Automação de Teste


O que você deve fazer:
Você deve criar um projeto baseado em Maven na sua IDE desenvolvimento favorita utilizando a linguagem de programação Java.

Forma de entrega:
Crie um repositório privado no GitHub com o nome src-cypress-web;
Efetue os commits de seu projeto neste repositório;
Não adicione ao repositório a pasta de projeto que sua IDE de desenvolvimento gera de forma automática;
Adicione os seguintes usuários ao repositório privado:
		no GitLab: sicredi_user (como “developer”)
Informe o nome do repositório na resposta do e-mail.

Adicione qualquer outra informação que você julgue relevante no e-mail ou em um arquivo readme.md

O que será avaliado?
Vai depender muito do seu perfil e conhecimento prévio sobre automação como, por exemplo, se você já usa o Selenium WebDriver há algum tempo, entre outros aspectos.
Mas temos análises comuns, que são:

•	O script deve executar com sucesso seguindo os passos descritos para o teste
•	O script não pode ter problema de validações
•	A execução do script não pode gerar exceções (exceptions) durante a execução
•	Uso dos locators
•	Boas práticas de desenvolvimento aplicado ao script de teste

Observação:
A entrega do Desafio 1 é obrigatória. A do Desafio 2 é opcional.

Desafio 1:

Observação:
O script deve executar no browser Google Chrome

Passos:

1.	Acessar a página:  https://www.grocerycrud.com/v1.x/demo/my_boss_is_in_a_hurry/bootstrap
2.	Mudar o valor da combo Select version para “Bootstrap V4 Theme”
3.	Clicar no botão Add Customer

4.	Preencher os campos do formulário com as seguintes informações:

Name: Teste Sicredi
Last name: Teste
ContactFirstName: seu nome
Phone: 51 9999-9999
AddressLine1: Av Assis Brasil, 3970
AddressLine2: Torre D
City: Porto Alegre
State: RS
PostalCode: 91000-000
Country: Brasil
from Employeer: Fixter
CreditLimit: 200

5.	Clicar no botão Save
6.	Validar a mensagem “Your data has been successfully stored into the database. Edit Customer or Go back to list” através de uma asserção
7.	Fechar o browser

Desafio 2:

Observação:
O script deve executar no browser Google Chrome

Pré-condição:
Execute todos os passos do Desafio 1

Passos:

1.	Clicar no link Go back to list
2.	Clicar na coluna “Search Name” e digitar o conteúdo do Name (Teste Sicredi)
3.	Clicar no checkbox abaixo da palavra Actions
4.	Clicar no botão Delete
5.	Validar o texto “Are you sure that you want to delete this 1 item?” através de uma asserção para a popup que será apresentada
6.	Clicar no botão Delete da popup, aparecerá uma mensagem dentro de um box verde na parte superior direito da tela. Adicione uma asserção na mensagem “Your data has been successfully deleted from the database.”
7.	Fechar o browser


Final do Desafio!
