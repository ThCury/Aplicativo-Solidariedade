# Caso de Uso Descritivo - ONG

### Nome: Gerência de ONG

#### Objetivo: Permitir que a ONG gerencie seus projetos, e aborde e estabeleça relação com os voluntários.

#### Ator Principal: ONG

#### Pré-condições: 

- A ONG deve estar logado no aplicativo como ONG;

#### Garantias de Sucesso/ Finalização:

- A ONG consegue estabelecer contato com os voluntários, e editar informações de seus projetos;

## Cenário Principal:

1. A ONG escolhe se deseja alterar informações cadastrais ou prosseguir e gerenciar seus projetos;
2. A ONG seleciona um projeto cadastrado pelo Host;
3. A ONG altera as informações cadastradas, como desejar;
4. O sistema atualiza os dados do projeto no banco de dados;
5. O sistema envia uma notificação para os voluntários, informando sobre vagas para as novas alterações;
6. A ONG, via aplicação, recebe as inscrições dos usuários;
7. A ONG pode iniciar uma conversa com os voluntários, para avaliar a entrada deles no projeto;
8. A ONG decide quais voluntários atuarão no Projeto Social;
9. A ONG pode manter um bate-papo com os voluntários cadastrados no Projeto;

### Fluxos Alternativos: 

AL1 - 2 - Caso a ONG não deseje alterar as informações de um projeto, o fluxo segue para 

### Fluxos de Exceção:

EX1 - 1-9 - Caso um Projeto seja excluído pelo Host durante as alterações da ONG, ao terminar as edições, deve ser retornado uma mensagem informando sobre a remoção do Projeto;

### Regras de Negócio: 

RN1 - Voluntários adicionados ao projeto devem ser notificados sobre futuras alterações cadastrais, e refazer sua inscrição, confirmando-a para os novos dados.
