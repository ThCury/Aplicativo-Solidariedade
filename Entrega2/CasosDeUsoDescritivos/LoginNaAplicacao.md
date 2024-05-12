# Caso de Uso Descritivo - Login de Usuário

### Nome: Cadastro de usuário

#### Objetivo: Permitir que o usuário realize Login na plataforma.

#### Ator Principal: Usuário.

#### Pré-condições: 

- O usuário deverá ter um cadastro realizado na aplicação;

#### Garantias de Sucesso/ Finalização:

- O usuário realiza o login, e pode gerenciar suas devidas demandas, com base no tipo de Login.

## Cenário Principal:

1. O usuário insere o e-mail e a senha;
2. O sistema valida os dados;
3. O usuário realiza o Login;

### Fluxos Alternativos: 

AL1 - 1 - Caso o usuário não saiba a senha, ele deverá selecionar a opção de "Esqueceu a senha", e redefiní-la via e-mail;

### Fluxos de Exceção:

EX1 - 2 - Caso o usuário insira uma senha incorreta, o sistema deverá retornar uma mensagem de erro, e enviá-lo à página de cadastro.
