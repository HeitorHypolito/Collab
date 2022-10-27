# Análise Dado
Nessse projeto foi estudado o uso da aleatoriedade no python para o desenvolvimento de um jogo. 
A lógica é fácil de se entender e consiste nas seguintes regras: 
O jogador deve lançar o dado 50 vezes, caso tire os números 1 ou 2, ele retorna uma casa, caso tire 3,4 ou 5 ele pode avançar uma casa
caso ele tire o número 6, ele pode jogar o dado novamente e o número tirado será referente à quantidade de casas que ele poderá andar.
O Objetivo é simples, chegar ao degrau de número 60 no prédio. 
Lembrando que foi colocada uuma restrição para que o jogador nao desça para andares "negativos" podendo chegar até o térreo. 
O entendimento do resultado foi por meio de análise probabilítica, ou seja, com o uso do histograma do matplotlib podemos verificara distribuição
de resultados nos 100 diferentes cenários estruturados. 
Além disos foi utilizada a biblioteca Numpy para a estruturação da aleatoriedade.
