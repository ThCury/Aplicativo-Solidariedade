# Caso de Uso Descritivo - Host do Projeto Social

### Nome: Gerência de Projetos Sociais

#### Objetivo: Permitir que o host do projeto gerencie projetos sociais dentro da aplicação.

#### Ator Principal: Host do Projeto

#### Pré-condições: 

- O host do Projeto social deve estar registrado no aplicativo;
- O host do Projeto social deve ter iniciado sessão no aplicativo;
- O host do projeto deve haver ao menos um projeto já previamente cadastrado;

#### Garantias de Sucesso/ Finalização:

- O projeto social tem suas informações atualizadas com sucesso no sistema;

## Cenário Principal:

1. O Host do Projeto seleciona a opção de Gerenciar projetos pré-existentes;
2. O sistema lista os Projetos sociais já cadastrados pelo Host;
3. O Host seleciona se deseja excluir ou editar um projeto;
4. O Host seleciona o projeto, dentre àqueles presentes na lista, para fazer as alterações;
5. O Host edita, podendo excluir, alterar, inserir ou remover informações cadastradas;
6. O sistema atualiza as informações em seu banco de dados;

### Fluxos Alternativos: 

AL1 - 5 - Caso o Host tenha optado por excluir um projeto, ele deverá confirmar a exclusão via e-mail, por motivos de segurança e proteção contra erros e possíveis invasões;

### Fluxos de Exceção:

EX1 - 2 - Caso o Host não tenha projetos cadastrados, ele deverá receber um alerta, informando sobre a situação, e redirecionando-o à parte de cadastro de projetos;

### Regras de Negócio: 

RN1 - Projetos sociais não podem ser excluídos caso tenham seu status como "Ativo", primeiro, o host deve inativá-los, e então apagá-los;
