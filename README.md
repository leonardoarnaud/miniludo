# MINI LUDO
-----------------------------------------
![alt text](https://i.ibb.co/K2J9d01/Capturar.png)

## Instruções iniciais:
- Temos um tabuleiro 6x6, 4 jogadores, cada um com uma cor de peça
- O vencedor é aquele que chegar no final do percurso com todas as 4 peças
- O inicio e o fim do percurso estão marcados com a cor mais escura
- As peças do player azul começam no quadrado 'C'. Ao jogar o dado para definir quantas casas vai pular, a direção da peça se inicia no 15 e vai pulando para o 16, 17, 18... e assim por diante. Ao chegar no 28 cotinua normalmente pelo 01, 02.
- No caso do azul, o quadrado 14 antecede a casa final que também está com a letra 'C'. Chegando ali a peça não pode mais avançar pois já alcançou seu objetivo
- Inicialmente não teremos jogo contra a máquina. A principio, vamos presumir que os 4 jogadores estão compartilhando o mesmo celular/tablet.
- Na vez de cada um, deve ser possível jogar um dado de 6 lados, escolher um peça e mover a quantidade de casas correspondente ao numero que cair
- Quando alguem conseguir colocar primeiro as quatro peças no quadro do centro respectivo a sua cor, o app deve abrir uma dialog e informando quem venceu e em seguida reiniciando jogo. Algo assim: "Vitória do Azul!" e um botão de OK.
- O jogo sempre começa com as vermelhas (A), depois é a vez  das verdes (B), depois azul (C) e por fim as amarelas (D)
- É importante neste inicio não deixar que se movam peças que não correspondem a cor da vez atual. Também deve respeitar o caminho na ordem numerica, não deixar o usuario mover peças por outros caminhos, nem pode deixar caminhar uma quantidade diferente de casas das que deram nos dados, exceto quando chega no final, que é onde não dá mais para avançar.
- O tabuleiro a cima é area central do aplicativo. Toda a interface de controle, botões, dados, imagem das peças, telas extras vão ficar a cargo da equipe discutir melhores soluções. O tabuleiro a cima reproduz a ideia central do jogo, mas equipe pode sim propor melhorias em tudo
- Vamos praticar implementação de testes também, isso ajuda a manter as coisas funcionando quando pessoas diferentes poem a mão no mesmo código
Dúvidas entre em contato. Não deixe participar!
Happy Code!
