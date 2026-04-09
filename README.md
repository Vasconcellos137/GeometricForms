
Site p/ usar comando clip-path: polygon();
https://bennettfeely.com/clippy/

Serve pra desenhar e recortar formas usando pontos
- você tem um bloco (div)
- escolhe pontos nele
- o CSS liga esses pontos
- tudo fora disso some

EX.
    polygon(50% 0%, 0% 100%, 100% 100%)

    Cada par é um ponto:
    - 50% 0% -> meio de cima, ou LINHA ESQUERDA.
    - 0% 100% -> canto esquerdo de baixo, ou LINHA DIREITA.
    - 100% 100% -> canto direito de baixo, ou  LINHA BASE.

    Final -> liga esses pontos -> vira triângulo.

"Dick's":

Triângulo..
2 primeiros pontos -> linha esquerda
2 do meio -> linha direita
2 últimos -> base 

Exagono..
