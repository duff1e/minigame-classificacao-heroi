# 🎮 MiniGame de Classificação de Herói

Este simples jogo interativo foi criado para o projeto de Classificador de Nível de Herói realizado para o **Bootcamp Potência Tech iFood: Programação do Zero** oferecido pela **DIO** numa bolsa concedida pelo **iFood**.

Seu objetivo era utilizar o conteúdo ensinado até então, como variáveis, estruturas condicionais, loopings e operadores, mas tomei a liberdade de incrementar o projeto um pouco mais e torná-lo mais visual. 

A linguagem de programação utilizada é o JavaScript, sendo ela o foco do Bootcamp, mas estruturei o projeto com HTML e CSS para rodá-lo em uma página web. 

A primeira etapa do programa é perguntar em um input o nome de herói do usuário. Logo em seguida, a interface, que consiste em uma pequena caixa, apresenta um monstro que deverá ser clicado para que um cálculo de XP ocorra. Ao clicar, é gerado um número aleatório entre 200~600 e adicionado ao XP total, a partir disso o programa segue para a classificação do herói, mostrando na tela em um prompt com a quantidade de XP obtida com a luta e o rank atual do herói, obdecendo a seguinte lista de XP total:

|   Rank   | Min | Max |
|----------|-----|-----|
|Ferro     |     |1000 |
|Bronze    |1001 |2000 |
|Prata     |2001 |6000 |
|Ouro      |6001 |7000 |
|Platina   |7001 |8000 |
|Ascendente|8001 |9000 |
|Imortal   |9001 |10000|
|Radiante  |10001|     |


Depois da mensagem, o looping recebe um `break` até ser ativado novamente ao clicar no monstro, onde fará todo o processo de cálculo de XP e classificação, assim como seus prompts.

Ao atingir o rank Radiante, o programa exibe uma mensagem informando que o herói atingiu o nível máximo e o programa se encerra.

Espero que gostem do pequeno projeto! Obrigada.