# Caso de Uso Descritivo - CADASTRO

### Nome: Cadastro de Usuário

#### Objetivo: Permitir que o usuário cadastre-se, conforme suas necessidades.

#### Ator Principal: Usuário.

#### Pré-condições: 

- O usuário não pode ter um login ativo no aplicativo;

#### Garantias de Sucesso/ Finalização:

- O usuário é cadastrado com sucesso na aplicação

## Cenário Principal:

1. O usuário entra na página de cadastro, informando seus dados e tipo de cadastro, como ONG, Host ou Voluntário;
2. O sistema valida os dados, conforme as regras estabelecidas de acordo com seu tipo de cadastro;
3. O sistema cadastra o novo usuário, e redireciona para a página de login;

### Fluxos Alternativos: 

AL1 - 2 - Caso o usuário já tenha um cadastro ativo, prossegue para a página de Login;

### Fluxos de Exceção:

EX1 - 2 - Caso o usuário cadastre-se como Host em uma ONG, a ONG deverá aceitar a solicitação, antes dos dados serem cadastrados.

### Regras de Negócio: 

RN1 - Só podem ser cadastrados Host's para Projetos com autorizações da ONG;
RN2 - Só podem ser cadastradas ONG's com registro válido e CNPJ ativo.
