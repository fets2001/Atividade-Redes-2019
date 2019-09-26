# Batalha Naval - Redes FatecSCS 2019

Equipe 3: André Luiz Dias dos Santos, Felipe Laranjeira, Nathan Saladino, Paschoal Dantas, Pedro Vasconcellos

O Jogo batalha naval simula dois tabuleiros, um servidor e um cliente por meio de UDP, onde podem ser colocados navios classificados em:

#### Submarinos 
Representados por "^", são estruturas de uma só casa tendo quatro no tabuleiro

#### Cruzadores
Representados por "+", são estruturas de duas casas tendo três no tabuleiro

#### Encouracados
Representados por um asterístico, são estruturas de três casas, tendo duas no tabuleiro

#### Porta Aviões
Representados por "&", é uma estrutura de quatro casas, tendo apenas um por tabuleiro

Cada estrutura de mais de uma casa pode ser feita em horizontal ou vertical, o objetivo do jogo é afundar todos navios do oponente. Cada um joga por um turno e quem afundar todos primeiro ganha. O jogo é feito em ascii art. Para atacar, é necessário dar as posições x e y do tabuleiro do oponente.
