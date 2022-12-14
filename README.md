# Dice-Game-RandomWalks
Olá. Esse é um mini projeto do meu curso de Python do DataCamp. <br>
O Objetivo é criar um jogo de dados em que o jogador tenha que chegar ao 60º degrau. <br>
Entretando não é tão fácil assim, dependendo de qual face do dado caia, o jogador irá subir ou descer.
* Se cair 1 ou 2, o jogador irá descer 1 degrau
* Se cair 3 a 5, o jogador irá subir 1 degrau
* Se cair 6, o jogador poderá rolar o dado de novo, sendo o número que cair a quantidade de degraus que irá subir.
Cada execução do código gerará um resultado "totalmente" aleatório e diferente da última vez
Além disso, será feito análises em gráficos de cada rodada <br>

A segunda parte do desafio era fazer com que o jogo mostrasse a probabilidade de ganhar. <br>
Para isso é necessário ter duas listas. 
* Uma para cada caminho aleatório que o código irá fazer;
* Outra para armazenar esse conjunto de caminhos aleatórios do código.
Ao utilizar gráficos, isso permite mostrar a relação entre Quantidade de Novos Jogos X Rodadas para Ganhar o jogo.
Ex:
* Na tentativa 20, foi necessário 50 rodadas
* 30 tentativas das 100 estipuladas levaram 50 rodadas

[Você pode acessar os arquivos no Kaggle por esse Link](https://www.kaggle.com/code/pedroingro/dice-game-randomwalks?scriptVersionId=113827547)

# Ferramentas
Foi usado nesse mini projeto:
* Python
* Matplotlib
* Numpy


# Desafio DataCamp - Resultados(Minha tentativa)
## Gráficos de uma simulação de jogo entre 2 Players
![Players](https://github.com/HawkEyeB/Images/blob/main/Dice%20Images/01%20-%20Jogadores%20.jpeg)
![Frequência dos Dados](https://github.com/HawkEyeB/Images/blob/main/Dice%20Images/02%20-%20Frequ%C3%AAncia%20de%20Dados.jpeg)

## Random Walks e Aleatóriedade
![RodadasXTentativas](https://github.com/HawkEyeB/Images/blob/main/Dice%20Images/03%20-%20Frequ%C3%AAncia.jpeg)
![RodadasXTentativas](https://github.com/HawkEyeB/Images/blob/main/Dice%20Images/04%20-%20PlotLine.jpeg)
