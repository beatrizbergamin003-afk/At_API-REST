# 📘 Conceitos de API REST

## O que é uma API?

API é a sigla para *Application Programming Interface*, que em português significa Interface de Programação de Aplicações. Ela funciona como uma ponte que permite que dois sistemas diferentes conversem e troquem informações de forma organizada. Em vez de um programa acessar diretamente o código ou o banco de dados de outro, ele faz pedidos pela API e recebe apenas o que precisa.

Uma boa analogia é pensar em uma tomada elétrica. Quando alguém conecta o carregador do celular na tomada, não precisa entender como funciona toda a rede elétrica da cidade. A tomada já foi criada para fornecer energia de maneira padronizada e segura. A API funciona do mesmo jeito: ela oferece uma forma simples e organizada para um sistema “se conectar” a outro sem precisar conhecer todos os detalhes internos.

---

## Para que serve uma API?

As APIs servem para permitir integração entre aplicações e serviços. Elas ajudam sistemas diferentes a compartilharem informações e funcionalidades sem complicação. Graças a isso, aplicativos conseguem usar mapas, pagamentos online, login com redes sociais e muitas outras funções sem precisar desenvolver tudo do zero.

Por exemplo, quando um aplicativo de música permite que alguém compartilhe uma canção diretamente no Instagram, existe uma API fazendo essa comunicação acontecer. É como usar um adaptador universal em uma viagem: mesmo que os aparelhos sejam diferentes, o adaptador cria uma conexão compatível para tudo funcionar corretamente.

---

## Por que as APIs são importantes?

As APIs são importantes porque tornam o desenvolvimento mais rápido, eficiente e organizado. Empresas conseguem aproveitar serviços já existentes em vez de criar novas soluções do zero, economizando tempo e recursos. Além disso, elas ajudam diferentes tecnologias a trabalharem juntas de forma segura.

Hoje, muitos serviços da internet dependem diretamente de APIs. Aplicativos de delivery, bancos digitais, redes sociais e plataformas de streaming usam APIs o tempo todo para trocar dados e oferecer recursos aos usuários. Sem elas, a comunicação entre sistemas seria muito mais complicada e limitada.

---

# 🌐 O que é REST?

REST é uma sigla para *Representational State Transfer*. Esse termo define um conjunto de princípios usados para organizar a comunicação entre sistemas na internet. Em vez de criar regras totalmente diferentes para cada aplicação, o modelo REST propõe uma forma padronizada de troca de informações usando recursos da própria web, como URLs e métodos HTTP.

Uma maneira simples de entender o REST é imaginar uma biblioteca. Cada livro possui um endereço específico na estante e qualquer pessoa pode pedir informações usando regras já conhecidas, como procurar, pegar, devolver ou atualizar um cadastro. O REST funciona de forma parecida: cada recurso de um sistema possui um endereço próprio, e as ações seguem padrões bem definidos para facilitar a comunicação.

---

## O que é uma API REST?

Uma API REST é uma API construída seguindo os princípios do REST. Ela permite que aplicações conversem entre si usando requisições HTTP, como GET, POST, PUT e DELETE. Cada uma dessas requisições representa uma ação diferente, como buscar informações, criar dados novos, atualizar registros ou remover conteúdos.

Por exemplo, em um aplicativo de filmes, uma API REST pode permitir listar filmes disponíveis, adicionar um novo título ou apagar um cadastro antigo. É parecido com usar um aplicativo de delivery: cada botão executa uma ação específica já esperada pelo sistema. Quando alguém toca em “fazer pedido”, o aplicativo envia uma solicitação padronizada, e o servidor entende exatamente o que precisa fazer.

---

## Por que APIs REST são tão utilizadas?

As APIs REST se tornaram populares porque são simples de entender e funcionam muito bem na internet. Como utilizam padrões já conhecidos da web, desenvolvedores conseguem criar integrações de forma mais rápida e organizada. Além disso, diferentes linguagens e plataformas conseguem se comunicar sem grandes dificuldades.

Outro ponto importante é a flexibilidade. APIs REST podem ser usadas em sites, aplicativos de celular, jogos e até dispositivos inteligentes. Isso faz com que elas sejam uma das soluções mais comuns para integração entre sistemas modernos, principalmente em aplicações que precisam trocar informações em tempo real.

---

# 🗂️ O que é CRUD?

CRUD é uma sigla usada para representar as quatro operações básicas realizadas em sistemas que trabalham com dados. As letras significam *Create, Read, Update* e *Delete*, ou seja: criar, ler, atualizar e apagar informações. Essas operações aparecem em praticamente qualquer aplicação que armazena dados, como redes sociais, lojas virtuais, aplicativos bancários e sistemas escolares.

Uma forma simples de entender o CRUD é pensar em uma agenda de contatos do celular. Quando alguém adiciona um novo contato, está realizando um Create. Ao abrir a agenda para visualizar um número, acontece um Read. Se o usuário altera o telefone de alguém, faz um Update. Já quando remove um contato antigo, realiza um Delete. Essas ações representam exatamente o funcionamento do CRUD em sistemas digitais.

---

## Create (C) e o método POST

O Create é a operação responsável por criar novos dados dentro do sistema. Em APIs REST, essa ação normalmente é feita usando o método HTTP POST. Quando um aplicativo envia informações novas para o servidor, o POST é utilizado para registrar esses dados.

No projeto, o Create foi implementado para permitir o cadastro de informações. É parecido com preencher um formulário online e clicar em “enviar”. O sistema recebe os dados enviados e cria um novo registro no banco de dados.

---

## Read (R) e o método GET

O Read serve para consultar ou visualizar informações já existentes. Em APIs REST, essa operação geralmente utiliza o método HTTP GET. Esse método faz uma solicitação ao servidor para buscar dados e devolvê-los ao usuário.

No projeto, o Read foi usado para listar ou consultar informações armazenadas. Um exemplo simples seria acessar um aplicativo de streaming e visualizar a lista de filmes disponíveis. Nesse caso, o sistema faz uma requisição GET para buscar os dados e mostrar o conteúdo na tela.

---

## Update (U) e o método PUT

O Update é utilizado para atualizar informações que já existem no sistema. O método HTTP mais associado a essa operação é o PUT, embora em alguns casos também possa ser usado o PATCH. Essa operação permite modificar dados sem precisar criar um novo registro.

Um exemplo seria editar o endereço em um aplicativo de entregas. Em vez de cadastrar tudo novamente, o sistema apenas altera a informação antiga para a nova. Mesmo que essa operação não tenha sido implementada no projeto, ela faz parte da estrutura completa do CRUD.

---

## Delete (D) e o método DELETE

O Delete é a operação responsável por remover dados do sistema. Em APIs REST, ela normalmente utiliza o método HTTP DELETE. Quando essa requisição é enviada, o servidor entende que aquele registro deve ser apagado.

Um exemplo do dia a dia seria excluir uma foto de uma rede social ou remover um produto do carrinho de compras. Embora o projeto tenha trabalhado apenas com Create e Read, o Delete é importante porque completa o conjunto das operações básicas usadas para gerenciar informações em aplicações modernas.

---

# 🌍 O que é HTTP?

HTTP significa *HyperText Transfer Protocol*. Ele é o protocolo usado para fazer a comunicação entre aplicações na internet. Toda vez que acessamos um site, usamos um aplicativo ou fazemos uma requisição para uma API, o HTTP é responsável por enviar as informações e trazer uma resposta do servidor.

Uma forma simples de entender o HTTP é imaginar uma conversa entre duas pessoas. Uma faz um pedido e a outra responde. Na internet funciona da mesma maneira: o cliente envia uma requisição e o servidor devolve uma resposta dizendo se deu certo ou se aconteceu algum problema. É isso que permite carregar páginas, enviar formulários e buscar informações online.

---

# 📌 O que são Status Codes?

Os *status codes* são códigos numéricos enviados pelo servidor para mostrar o resultado de uma requisição HTTP. Eles servem para indicar se a operação funcionou corretamente ou se ocorreu algum erro durante o processo.

Esses códigos são importantes porque ajudam a entender o que aconteceu em cada requisição. Em vez do sistema apenas dizer que deu erro, ele mostra exatamente qual foi o problema. Isso facilita bastante na hora de testar a API e corrigir falhas no desenvolvimento.

---

## Status codes utilizados em APIs

| Código | Significado |
|---|---|
| 200 OK | Requisição realizada com sucesso |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/b390fc16-3db1-4032-b76d-4ffb7b3b6bcd" />

| 201 Created | Novo dado criado corretamente |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/1f472df4-7efe-4417-addb-0791a5e628ea" />

| 400 Bad Request | Requisição inválida ou incompleta |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/a7f69f62-d8d6-437f-8685-ce469d7fab5e" />

| 401 Unauthorized | Usuário sem autorização |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/fcf62c6f-4320-4b3a-b519-a809f094ccf2" />

| 404 Not Found | Rota ou recurso não encontrado |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/84d34244-3048-456c-b8a7-d11afadc4be8" />

| 500 Internal Server Error | Erro interno no servidor |
<img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/8b950982-034b-432c-a389-3f3a32fb06dc" />

---

## Por que os status codes são importantes?

Os status codes são importantes porque deixam a comunicação entre cliente e servidor mais organizada e fácil de entender. Com eles, fica muito mais simples identificar se uma requisição funcionou corretamente ou se existe algum problema acontecendo na aplicação.

Além disso, eles ajudam bastante durante o desenvolvimento da API. Quando fazemos testes no projeto, conseguimos entender rapidamente o resultado de cada requisição apenas olhando o código retornado pelo servidor. Isso facilita encontrar erros, corrigir problemas e garantir que a aplicação esteja funcionando corretamente.

---

# 📦 O que é JSON?

JSON significa *JavaScript Object Notation*. Ele é um formato usado para organizar e trocar informações entre sistemas de forma simples. Em APIs, o JSON é muito utilizado porque consegue armazenar dados de maneira organizada e fácil de entender.

Uma forma simples de visualizar o JSON é pensar em um cadastro. Cada dado possui um nome e um valor correspondente. Isso facilita bastante a comunicação entre cliente e servidor, já que os dados ficam organizados de um jeito padronizado e fácil de interpretar.

---

## Como funciona o formato JSON?

O JSON utiliza chaves `{}` para representar objetos e colchetes `[]` para listas. Dentro dessas estruturas, os dados ficam separados em pares de chave e valor. Isso ajuda a deixar as informações mais organizadas e simples de ler.

### Exemplo de JSON

```json
{
  "id": 1,
  "nome": "Beatriz",
  "email": "beatriz@email.com"
}
```

Nesse exemplo, o JSON representa um usuário com informações como id, nome e email. Esse formato facilita bastante porque tanto a API quanto a aplicação conseguem entender os dados rapidamente.

---

## Por que usamos JSON em APIs?

O JSON é muito usado em APIs porque ele é leve, simples e compatível com várias linguagens de programação. Isso facilita bastante a comunicação entre diferentes sistemas, já que praticamente qualquer tecnologia consegue trabalhar com esse formato.

Além disso, o JSON deixa as respostas da API mais organizadas e fáceis de entender. No projeto, por exemplo, quando fazemos uma requisição GET, os dados retornam em JSON justamente porque esse formato ajuda na troca de informações entre cliente e servidor de forma prática e eficiente.

---

# 🔗 Rotas da API

## GET /api/dados

Essa rota usa o método GET para listar todos os dados cadastrados na API. Ela serve para consultar as informações que já estão salvas no sistema.

Essa rota não possui parâmetros, porque ela retorna todos os registros cadastrados.

### Exemplo de requisição

```http
GET http://localhost:3000/api/dados
```

### Exemplo de resposta de sucesso

```json
Status: 200 OK

[
  {
    "id": 1,
    "nome": "João",
    "email": "joao@email.com"
  },
  {
    "id": 2,
    "nome": "Maria",
    "email": "maria@email.com"
  }
]
```

### Exemplo de resposta de erro

```json
Status: 500 Internal Server Error

{
  "erro": "Erro ao buscar os dados"
}
```

---

## GET /api/dados/:id

Essa rota usa o método GET para buscar um registro específico através do ID. Ela serve para retornar apenas uma informação cadastrada no sistema.

O parâmetro utilizado é o `id`, que representa o identificador do registro que será consultado.

### Exemplo de requisição

```http
GET http://localhost:3000/api/dados/1
```

### Exemplo de resposta de sucesso

```json
Status: 200 OK

{
  "id": 1,
  "nome": "João",
  "email": "joao@email.com"
}
```

### Exemplo de resposta de erro

```json
Status: 404 Not Found

{
  "erro": "Registro não encontrado"
}
```

---

## POST /api/dados

Essa rota usa o método POST para cadastrar novas informações na API. Ela serve para criar um novo registro no sistema a partir dos dados enviados pelo usuário.

Para essa rota funcionar corretamente, é necessário enviar um body em JSON com as informações que serão cadastradas.

### Exemplo de requisição

```http
POST http://localhost:3000/api/dados
```

```json
{
  "nome": "Beatriz",
  "email": "beatriz@email.com"
}
```

### Exemplo de resposta de sucesso

```json
Status: 201 Created

{
  "id": 3,
  "nome": "Beatriz",
  "email": "beatriz@email.com"
}
```

### Exemplo de resposta de erro

```json
Status: 400 Bad Request

{
  "erro": "Dados inválidos"
}
```

---

# 🏗️ Diagrama da Arquitetura
<img width="1024" height="662" alt="image" src="https://github.com/user-attachments/assets/25d34580-3c10-484e-9fb5-365d40cb52f3" />
O diagrama mostra como acontece a comunicação entre todas as partes do sistema, desde os sensores conectados ao ESP-32 até a API, o banco de dados em memória e o cliente que faz as requisições.

## Detalhamento do Fluxo

### Leitura dos dados

Os sensores de temperatura e umidade fazem a coleta das informações do ambiente. O ESP-32 é responsável por ler esses dados dos sensores para depois conseguir enviar tudo para a API.

### Envio para a API

Depois de receber os dados dos sensores, o ESP-32 envia essas informações para a API usando uma requisição HTTP do tipo POST. Os dados são enviados em formato JSON para que a API consiga processar e armazenar as informações corretamente.

### Funcionamento da API

A API desenvolvida em Node.js/Express funciona como o back-end do sistema. Ela recebe os dados enviados pelo ESP-32, faz o gerenciamento das informações e realiza a comunicação com o banco de dados em memória usando métodos HTTP como GET e POST.

### Comunicação com o cliente

O cliente, que pode ser o Postman ou futuramente um aplicativo ou site, faz requisições HTTP para a API. As requisições GET servem para consultar os dados armazenados e o POST pode ser usado para enviar novas informações. As respostas da API retornam em formato JSON junto com os status codes indicando o resultado da operação.


# Como rodar o projeto

## Pré-requisitos

Para conseguir executar o projeto, é necessário ter o Node.js instalado no computador. No nosso projeto foi utilizada uma versão mais recente do Node.js para conseguir rodar o servidor corretamente.

Também é necessário ter o npm instalado, que normalmente já vem junto com o Node.js.

---

## Instalação das dependências

Depois de baixar o projeto, é preciso instalar as dependências utilizadas na API. Para isso, basta abrir o terminal na pasta do projeto e executar o seguinte comando:

```bash
npm install
```

Esse comando instala todas as bibliotecas necessárias para o funcionamento da aplicação.

---

## Como executar o servidor

Depois da instalação das dependências, o servidor pode ser iniciado com o comando:

```bash
node server.js
```

Após executar esse comando, a API será iniciada localmente.

---

## Como saber se está funcionando

Quando o servidor iniciar corretamente, uma mensagem aparecerá no terminal informando que a aplicação está rodando, normalmente mostrando a porta utilizada, como por exemplo:

```bash
Servidor rodando na porta 3000
```

Isso significa que a API já está pronta para receber requisições.

---

## Como testar no Postman

Para testar a API, basta abrir o Postman e fazer uma requisição para uma das rotas criadas no projeto.

### Exemplo de requisição GET

```http
GET http://localhost:3000/api/dados
```

### Exemplo de requisição POST

```http
POST http://localhost:3000/api/dados
```

### Body em JSON

```json
{
  "nome": "Carlos",
  "email": "carlos@email.com"
}
```

---

# Tecnologias usadas

- **Node.js** — ambiente utilizado para executar o JavaScript no servidor.
- **Express** — framework utilizado para facilitar a criação das rotas e da API.
- **JavaScript** — linguagem utilizada no desenvolvimento do projeto.
- **Postman** — ferramenta utilizada para testar as requisições da API.
- **JSON** — formato utilizado para enviar e receber dados na API.
- **HTTP** — protocolo utilizado para realizar a comunicação entre cliente e servidor.

---

# Reflexão sobre a atividade

O que eu mais gostei nessa atividade foi entender como funciona a comunicação entre cliente e servidor em uma API. Achei interessante conseguir criar rotas, testar requisições no Postman e ver os dados sendo enviados e retornados em JSON.

A maior dificuldade foi entender melhor os métodos HTTP e os status codes no começo, porque existem vários tipos diferentes e cada um possui uma função específica. Também foi um desafio aprender a organizar as rotas e estruturar corretamente as respostas da API.
````
