Desafio de recrutamento de full-stack
====================================
Este repositório contém o desafio de recrutamento para a vaga de full-stack.

Este desafio tem como objetivos avaliar seu conhecimento técnico, aprendizado, e como você lida com prazos, requisitos e com uma situação muito semelhante às que você enfrentará no trabalho.

---
## Descrição do desafio

Seu objetivo será implementar um mockup do dashboard do nosso site e uma página de gerenciamento das matérias (disciplinas).

O dashboard é a nossa página principal, para o qual o aluno é levado após o login. Nela apresentamos todas as matérias para o aluno e ele pode explorar as matérias que oferecemos para a sua faculdade, e a partir dela chegar ao conteúdo que ele deseja estudar. Se você já usou algum site de cursos online (eg. *Coursera, Khan Academy, Duolingo...*) ou serviços de vídeo como *YouTube* ou *Netflix* você pode estar familiarizado com a função que o dashboard desempenha.

A página de gerenciamento das matérias é onde nós criamos as matérias que serão exibidas aos alunos. Além do processo de criação, nessa página conseguimos editar uma matéria quando necessário, e também podemos excluí-la. Basicamente, esta página conta com as quatro operações básicas usadas em banco de dados relacionais, também conhecida CRUD (Create, Read, Update e Delete).

<img src="./screens/dash.png" width="100%"/>

## Requisitos

- Sua missão será criar uma página onde fazemos todo o gerenciamento das matérias persistidas em um banco de dados relacional. As matérias devem ser dos tipos personalizadas (matérias que criamos para faculdades específicas) e matérias gerais, em ambos os tipos temos os seguintes dados: **Nome** e **Descrição**. 

- O sistema deve apresentar um dashboard de listagem de matérias, separadas entre matérias personalizadas e matérias gerais.

- O sistema deve esconder uma matéria do dashboard, mas não necessariamente excluir, apenas deixar invisível ao aluno no dashboard, mantendo o registro na base de dados. 

- **Não se preocupe em reproduzir o design da nossa tela**, ela está incluída apenas como inspiração, o que iremos analisar é como você **cria**, **persiste** e **exibe os dados** e que seja **funcional**.

- Você tem total liberdade para decidir qual stack / tecnologias irá utilizar.

- Estamos fornecendo na pasta assets um json contendo alguns dados (nome e descrição) de matérias para ter um ponto de partida.

## Critérios de avaliação

A sua solução será avaliada segundo os seguintes critérios.

- Funcionalidade
- Prazo de 7 dias a partir do recebimento deste desafio.

Definimos também critérios que não são absolutamente necessários mas valem pontos extras:

- Login para acesso aos dados com diferentes níveis de acesso;
- Uso da linguagem PHP;
- Uso do docker e docker-compose;
- Incluir alguma funcionalidade extra.

## Entregáveis

A solução deve ser entregue na forma de um link com um repositório hospedando o seu código, o README deve conter instruções de como executá-lo. Deve ser enviado para para o e-mail victor.magalhaes@esp.ce.gov.br

---
Qualquer duvida entre em contato conosco victor.magalhaes@esp.ce.gov.br.  
Boa Sorte!