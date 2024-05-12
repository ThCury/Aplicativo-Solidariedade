###Caso de Uso Descritivo - Host do Projeto Social

##Nome: Cadastro de Projetos Sociais

##Objetivo: Permitir que o host do projeto cadastre projetos sociais dentro da aplicação.

##Ator Principal: Host do Projeto

##Pré-condições: 

- O host do Projeto social deve estar registrado no aplicativo;
- O host do Projeto social deve ter iniciado sessão no aplicativo;

##Garantias de Sucesso/ Finalização:

- O projeto social é cadastrado com sucesso no sistema;

##Cenário Principal:

1. O host do Projeto seleciona a opção de cadastrar novo Projeto na aplicação;
2. O host insere as informações específicas do Projeto Social, de acordo com as regras de Negócio;
3. O sistema valida as informações conforme as regras de Negócio;
4. O sistema realiza o cadastro do sistema no Banco de Dados;

##Fluxos Alternativos: 

AL1 - 3 - Caso as informações não estejam válidas de acordo com as regras de negócio, o sistema deve retornar uma mensagem especificando as regras de negócio que estão sendo violadas, e retornar ao item 2, para que o Host do projeto altere as informações em desacordo;

##Fluxos de Exceção:

EX1 - 1-4 - Caso o Usuário opte por não prosseguir com o cadastro, deverá cancelar as informações, e os dados deverão ser ignorados;

EX2 - 1 - Caso o Host do projeto tenha alguma pendência em seu cadastro, ou seja, não esteja devidamente cadastrado no sistema, o mesmo não deverá ser capaz de inserir um novo Projeto;

##Regras de Negócio: 

RN1 - Projetos sociais só podem ser cadastrados com status "ativo".
