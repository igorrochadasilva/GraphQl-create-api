## Projeto Frontend Vue + Apollo Client

**Visão Geral da Aplicação**

- Apenas detalhes da aplicação.

**Como o Projeto foi Criado?**

- `npx vue create {app name}`

**Entendendo LocalStorage**

- Setando valores no localStorage e buscando eles.

**Configurando Apollo Client**

- Criado arquivo `graphql.js` no plugins
- Configurado AppoloClient

**Obter Perfis**

- Criado query para obter perfis no método `obterPerfis`.

**Registrar Usuário**

- Criado mutation de registrarUsuario no método `registrar`

**Componente Usuário Logado**

- Updated `setUsuario` in `store.js` file and valid token to set
- Criado query Login e setando usuario dados no context do vue

**Lista de Usuários**

- Criando query Lista de usuários
- Setando parâmetro `fetchPolicy: network-only` na query para buscar somente na rede e não no cache

**Consultar Usuário Usando Filtro**

- Criando query de consulta de usuário.

**Cadastrar Novo Usuário**

- Criando mutation de novo usuário.

**Alterar Usuário**

- Criando mutation de alterar usuário.

**Excluir Usuário**

- Criado mutation de exclusão de usuário

**Desafio Perfil**

- Criação de queries do perfil

**Desafio Perfil - Resposta**

**Recursos úteis**

Links Úteis

https://www.apollographql.com/docs/link/

https://www.w3schools.com/html/html5_webstorage.asp

https://vuejs.org/

https://cli.vuejs.org/guide/installation.html

https://vuetifyjs.com/en/
