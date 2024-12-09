# Shadow Duel - Jogo RPG de cartas 

Shadow Duel é um jogo de RPG de batalha de cartas em que os jogadores colecionam cartas de personagens, formando um baralho estratégico para duelos. O jogo se passa em um universo sombrio e místico, onde diferentes classes competem pela controle de poderes ocultos.

### Equipe
- Luccas Noschang
- Jéssica Dhesseffer
- Isadora Carminatti
- Estevão Limas Junior
- Vinicios Ferreira dos Santos
  
<hr>

### Tópicos
- [Equipe](#equipe)  
- [Protótipo Login e Cadastro de Usuário (Sprint 01)](#protótipo-login-e-cadastro-usuário-sprint-01)  
- [Protótipo de Telas dos Requisitos (Sprint 02)](#protótipo-de-telas-dos-requisitos-sprint-02)  
- [Protótipo das Telas (Sprint 03)](#protótipo-das-telas-sprint-03)  
- [Implementação da Tela de Cadastro e Login (Sprint 04)](#implementação-da-tela-de-cadastro-e-login-sprint-04)  
- [Telas de Cadastro de Negócio (Sprint 05)](#telas-de-cadastro-de-negócio-sprint-05)  
- [Telas de Relatórios de Negócio (Sprint 06)](#telas-de-relatórios-de-negócio-sprint-06)  
- [Requisitos para Instalação](#requisitos-para-instalação)  

<hr>

## Protótipo Login e cadastro usuário (Sprint 01)

Protótipos das páginas para autenticação de usuários, permitindo login com e-mail e senha ou criação de uma nova conta por meio de um formulário básico.

<div class="LoginECadastro" align="center">
  <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/Cadastro.png" width="500px"/>
  <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/Login.png" width="500px"/>
</div>

<hr>

## Protótipo de telas dos requisitos (Sprint 02)

Os requisitos funcionais definidos para o projeto são os seguintes:

Requisito Funcional 1: O sistema deve permitir que o usuário crie uma conta e faça login para acessar o jogo, mantendo um histórico de partidas e pontuações.
Requisito Funcional 2: O jogo deve permitir a criação de partidas, onde os jogadores podem escolher um deck de cartas e jogar contra personagens do próprio jogo.
Requisito Funcional 3: O sistema deve comparar automaticamente os atributos das cartas selecionadas pelos jogadores e determinar o vencedor da rodada, atualizando a pontuação do jogador.

<hr>

## Protótipo das telas (Sprint 03)

As telas desenvolvidas no protótipo incluem:

Caminho: Permite ao jogador escolher seu deck inicial, que será utilizado nas batalhas.

<div class="Caminho" align="center"> <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/Escolher%20o%20caminho%20(3).png" width="800px"/> </div>
<br>

Batalhas: Uma espécie de mapa onde o jogador seleciona um deck para batalhar.

<div class="Batalhas" align="center"> <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/TelaBatalhas.png" width="800px"/> </div>
<br>

 Perfil: Mostra o nome do jogador, a quantidade de moedas e os decks adquiridos.

<div class="Perfil" align="center"> <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/TelaPerfil.png" width="800px"/> </div>
<br>

Decks: Lista todos os decks comprados, incluindo o inicial, e exibe as cartas que cada deck contém.

<div class="Decks" align="center"> <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/TelaDecks.png" width="800px"/> </div>
<br>

Loja: Oferece a opção de comprar mais cartas e decks, além do inicial. Os decks disponíveis incluem Goblin, Mago, Esqueleto e Guerreiro.

<div class="Loja" align="center"> <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/TelaLoja.png" width="800px"/> </div>
<br>

<hr>

## Implementação da Tela de Cadastro e Login (Sprint 04)

Nesta sprint, as telas de login e cadastro foram implementadas com melhorias visuais, como a adição de um fundo atualizado e reposicionamento do formulário para a direita.

<div class="LoginECadastro" align="center"> 
  <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/Captura%20de%20tela%202024-12-08%20181459.png" width="500px"/> 
  <img src="https://github.com/luccasnoschang/ShadowDuel/blob/main/src/assets/images/Captura%20de%20tela%202024-12-08%20181524.png" width="500px"/>
</div>

<hr>

## Telas de cadastro de negócio (Sprint 05)

As telas de Caminho e Loja foram concluídas com interatividade para o usuário (cadastro e edição de registros).

- Caminho: Permite ao jogador selecionar o deck inicial para batalhar.

<div align="center"> <img src="" width="800px"/> </div>
  
- Loja: Disponibiliza cartas e decks adicionais para compra.

<div align="center"> <img src="" width="800px"/> </div>

<hr>

## Telas de relatórios de negócio (Sprint 06)

As telas de Perfil e Decks foram concluidas com apresentação de dados aos usuários.

- Perfil: Exibe informações do usuário, como nome, moedas disponíveis e decks adquiridos.

<div align="center"> <img src="" width="1000px"/> </div>

- Decks: Mostra os decks disponíveis e as cartas pertencentes a cada um deles.

<div align="center"> <img src="" width="1000px"/> </div>

<hr>

# Requisitos para Instalação

1. Clone o repositório do front-end no seu terminal:

```
git clone https://github.com/Juniorelzin/Shadow_Duel_Front
cd Shadow_Duel_Front/src
code .
npm install
npm run dev
```

2. Clone o repositório do back-end:

```
git clone https://github.com/Juniorelzin/Shadow_Duel_Back
```

3. Execute o back-end utilizando a extensão `Spring Boot Extension Pack`.


