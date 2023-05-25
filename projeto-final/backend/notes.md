## Projeto Backend com Graphql

**Introdução**

**Configuração do Projeto**

- Rodando migrations
- Criando tabelas
- Instalando dependências
- `npx knex migrate:latest`

**Diferenças nas migrations**

**Criando Arquivo .env**

- Criação de file .env e chaves de acesso.

**Registrar Usuário**

- Criação de mutation registrarNovoUsuario
- Utilização do bcrypt para criptografia de senha
- Validação de recebimento de dados na mutation de registrar e alterar usuário

**O que é Token JWT**

- JWT é um json web token que serve como verificação de acesso.
- O token possui: header, payload, signature
- header: tipo e algoritimo.
- payload: conteudo do seu token.
- signature: assinatura do token

**Login de Usuário**

- Criação de pasta comum
- Criação de file usuario, para criação de token jwt para usuario logado.
- Criação de query login, com retorno de token jwt.

**Usando Context #01**

- Criando contexto de maneira onde se possa utilizar dados e funções em qualquer area do projeto.
- Passando token jwt para contexto, para ser utilizado no fluxo logado do usuário

**Simulando o Login**

- Criando simulador de usuário logado
- Retornando usuário e passando token de usuário no header da requisição
- Salvando token no context

**Usando Context #02**

- Acessando token, e validando se não expirou para pegar dados do usuario
- Retornando no contexto informações do usuario, admin e validação de ambas as informações

**Aplicar Autenticação**

- criando autenticação e utilizando nas ações no banco de dados.
- Validando se é usuario admin ou não nas mutations.

**Correção alterar usuário**

- Criado validação para usuario somente alterar perfil após validação

**Aplicar Autenticação #2**

- Aplicando autenticação em cima das consultas de usuários e perfil

**Conclusão do Módulo**

**Recursos do módulo & Links úteis**

- Links Úteis

- https://jwt.io/

- https://graphql.org/learn/execution/#root-fields-resolvers

- https://www.apollographql.com/docs/apollo-server/essentials/data#context
