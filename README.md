
# Desafio Front End - Squad Management Tool

Olá, gostaríamos de dizer que estamos muito felizes pelo seu interesse em nossa vaga e lhe convidar a participar do nosso desafio técnico.  😁

O que avaliamos:

-   Seu código
-   Organização
-   Boas práticas de programação
-   Boas práticas de UI/UX
- Componentização

### Desafio

Para esse desafio, você precisará criar uma aplicação **responsiva** em ReactJS onde o usuário será capaz de gerenciar times de futebol - criar, deletar e editar - sejam eles reais ou fantasia, seguindo estritamente o layout proposto a seguir:

##### Página inicial
![Home](https://github.com/BitspaceSolutions/desafio-front-end/blob/main/home.jpg?raw=true)

##### Página de criação/edição de time
![Create/Edit team](https://github.com/BitspaceSolutions/desafio-front-end/blob/main/team.jpg?raw=true)

#### Regras de Negócio
##### Página inicial
- O usuário deve ser capaz de ter uma visão geral dos times cadastrados, através de uma listagem em uma tabela.
	-  A tabela deve permitir que os times sejam **ordenados alfabeticamente** por nome ou descrição.
	- O usuário deve ser capaz de **deletar** ou **editar** um time existente.
	
- O painel deve conter um indicador com os 5 times com **maior/menor média de idade** entre seus jogadores.
- O painel deve conter um indicador com os dois jogadores **mais** e **menos** escolhidos dentre todos os times criados.
	- Ao passar o mouse por cima das iniciais dos jogadores, devem ser exibido um `tooltip` com as seguintes informações do jogador: nome, idade e nacionalidade

##### Página de criação/edição de time
- Todos os campos do formulário são obrigatórios.
- Caso o usuário deixe algum campo em branco ou preencha incorretamente o campo, o campo correspondente deve ser **sinalizado** e **apresentar uma mensagem de erro**.
	- O campo `Team website` deve apenas aceitar um valor válido de website (http/https)
- O campo `Tags` deve gerar uma nova tag no input quando o usuário pressionar `Enter` ou `;`
- Ao alterar a formação do time, todas as posições devem ser **resetadas**.
- Deve-se utilizar **drag'n drop** para inserir o card do jogador na posição desejada
	- Ao adicionar um jogador no time, ele não deve mais aparecer como opção disponível na lista de jogadores.
	- Quando o jogador for adicionado em uma posição, suas iniciais do **primeiro** e **último** nome devem ser exibidas no local correspondente.
	- Ao passar o mouse por cima das iniciais dos jogadores, devem ser exibido um `tooltip` com as seguintes informações do jogador: **nome, idade e nacionalidade**


Para fazer a listagem dos jogadores, utilize a seguinte API:  [API-FOOTBALL](https://www.api-football.com/).

#### Diferenciais
-   TypeScript;
-   NextJS;
- Testes;
-   Hospedar a aplicação na Vercel ou em algum outro host;


### Entrega do Projeto

O prazo de entrega do projeto é de  **7 dias**. Ao finalizar, você deve criar um repositório público com o código e a documentação para testarmos o projeto. Se você conseguir hospedá-lo em algum host, não esqueça de incluir o link para a Demo.


