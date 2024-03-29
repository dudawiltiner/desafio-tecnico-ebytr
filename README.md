
# Desafio Ebytr - *To Do List*

## Boas vindas ao repositório do Desafio Técnico - Caso da empresa Ebytr

Esse desafio foi proposto pela [Trybe](https://www.betrybe.com/), em que foram requisitadas habilidades necessáiras para desenvolver um projeto **Full Stack**. O resultado final é uma plataforma para **organização e acompanhamento das tarefas** pelos colaboradores da empresa fictícia Ebytr, salvando dados num banco de dados **NoSQL** através de uma **API RESTFull**.

---

## Sumário

- [Contexto do *Case*](#contexto-do-case)
  - [Requisitos técnicos](#requisitos-técnicos)
  - [Funcionalidades](#funcionalidades)
- [Entregáveis](#entregáveis)
- [Usando a plataforma](#usando-a-plataforma)
  - [Primeiro Acesso](#primeiro-acesso)
  - [Criando uma tarefa](#criando-uma-tarefa)
  - [Atualizando uma tarefa](#atualizando-uma-tarefa)
  - [Excluindo uma tarefa](#excluindo-uma-tarefa)
  - [Ordenando a Lista de Tarefas](#ordenando-a-lista-de-tarefas)
  - [Filtrar as tarefas](#filtrar-as-tarefas)
  - [Digitando a URL de forma errada](#digitando-a-url-de-forma-errada)
  - [Realizando o *Logout*](#realizando-o-logout)
  - [Acessando pelo celular](#acessando-pelo-celular)
- [Link para o deploy da Plataforma](#link-para-o-deploy-da-plataforma)
---

## Contexto do *Case*

*"A empresa **Ebytr** está passando por problemas de produtividade/controle porque as pessoas colaboradoras vêm tendo dificuldade na organização de suas tarefas individuais. Por esse motivo, a diretora de produto Carolina Bigonha decidiu implantar **uma nova forma de organizar as tarefas.**"*

*"Você foi a pessoa contratada para desenvolver um sistema capaz de **auxiliar as pessoas colaboradoras a se organizar e ter mais produtividade**.
Na Ebytr o time de desenvolvimento utiliza a **Stack MERN** para criar suas aplicações. Foi combinado com a Ebytr que você utilizará essa mesma Stack para resolver o problema de organização e produtividade da empresa."*

Abaixo estão os requisitos técnicos e as funcionalidades que a solução deve possuir:

### Requisitos técnicos

- [x] Front-End em React;
- [x] Back-End em NodeJS, com MongoDB;
- [x] Arquitetura em camadas;

### Funcionalidades

- [x] Visualizar a lista de tarefas;
- [x] Esta lista deve ser ordenável por ordem alfabética, data de criação ou por status;
- [x] Inserir uma nova tarefa na lista;
- [x] Remover uma tarefa da lista;
- [x] Atualizar uma tarefa da lista;
- [x] A tarefa deve possuir um status editável: pendente, em andamento ou pronto;

## Entregáveis

A solução do desafio foi separarada em duas partes: front-end e back-end, e para o controle de versionamento de cada uma delas foram criados os seus respectivos repositórios:

- [Repositório com o backend](https://github.com/dudawiltiner/desafio-backend-ebytr).

- [Repositório com o frontend](https://github.com/dudawiltiner/desafio-frontend-ebytr);

---

## Usando a plataforma

Após cada um dos passos a seguir, haverá um exemplo de como cada página pode ser usada, caso tenha dificuldades e o exemplo não seja suficiente, não hesite em me contatar em _eduardawiltiner@gmail.com_.

### Primeiro Acesso

Acessando a plataforma neste [link](https://desafioebytr.vercel.app/) , você irá encontrar a tela de **Login**, será onde você deverá se autenticar para ter acesso ao acompanhamento das tarefas na página **Home**. Sem a autenticação você não terá acesso a Home, mas quando autenticado(a) você não terá que fazer o *login* novamente quando fechar a página e abri-la depois durante 24h.

<div align="center">
  <img src="./gifs/login.gif" margin="10px" width="700" alt="login"/>
</div>

### Criando uma tarefa

Para criar uma tarefa, você deve apenas clicar no "+" a direita do título "Lista de Tarefas". Uma data de prazo já estará configurada para o mesmo dia de criação da tarefa, mas você pode modificá-la.

<div align="center">
  <img src="./gifs/createTask.gif" margin="10px" width="700" alt="criando uma tarefa"/>
</div>

### Atualizando uma tarefa

Para atualizar uma tarefa, você deve apenas clicar no símbolo de edição à direita de cada tarefa. E você pode perceber que a mudança de status vai interferir na barra de progresso das atividades.

<div align="center">
  <img src="./gifs/updateTask.gif" margin="10px" width="700" alt="atualizando uma tarefa"/>
</div>
  
### Excluindo uma tarefa

Para excluir uma tarefa, você deve apenas clicar no símbolo de edição à direita de cada tarefa e, logo depois, clicar no botão "Remover". E você pode perceber que a mudança de status vai interferir diretamente na barra de progresso.

<div align="center">
  <img src="./gifs/removeTask.gif" margin="10px" width="700" alt="excluindo uma tarefa"/>
</div>

### Ordenando a Lista de Tarefas

Você pode ordenar a lista de forma alfabética, pelo status e por data de criação clicando nos botões correspondentes.

<div align="center">
  <img src="./gifs/order.gif" margin="10px" width="700" alt="order a lista"/>
</div>

### Filtrar as tarefas

Você pode filtrar as tarefas para aparecer apenas as que estão sob a sua responsabilidade. (recurso implementado recentemente)

<div align="center">
  <img src="./gifs/filter.gif" margin="10px" width="700" alt="filtro de tarefas"/>
</div>

### Digitando a URL de forma errada

Ao digitar a URL do site de forma errada, não se preocupe, vai paracer a página de erro 404 que vai te ajudar a voltar a **Home**.

<div align="center">
  <img src="./gifs/404.gif" margin="10px" width="700" alt="erro 404"/>
</div>
  
### Realizando o *Logout*

Para se desconectar da sua conta, só é necessário clicar em seu nome no NavBar e, em seguida, clicar em "Sair".

<div align="center">
  <img src="./gifs/logout.gif" margin="10px" width="700" alt="saindo da plataforma" />
</div>

### Acessando pelo celular

A plataforma não possui uma versão *mobile*, logo se você tentar usar pelo celular visualizará apenas um aviso sobre isso.

<div align="center">
  <img src="./gifs/nomobile.gif" margin="10px" width="700" alt="sem versão mobile" />
</div>

## Link para o deploy da Plataforma:
https://desafioebytr.vercel.app/

OBS:Lembrando que para acessar a plataforma deve possuir um cadastro no banco de dados.
