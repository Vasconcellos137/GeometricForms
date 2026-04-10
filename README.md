
Site p/ usar comando clip-path: polygon();
https://bennettfeely.com/clippy/

Serve pra desenhar e recortar formas usando pontos
- você tem um bloco (div)
- escolhe pontos nele
- o CSS liga esses pontos
- tudo fora disso some

As figuras são feitas usando esse comando: clip-path: polygon()
- Onde cada par de números representa um ponto dentro da figura.
- Esses pontos são ligados em sequência, formando o desenho. É importante colocar os pontos
em uma ordem lógica, geralmente no sentido horário, para que a forma não fique distorcida. 
- Mudando os valores dos pontos, é possível criar diferentes formas geométricas.

Em resumo, serve pra desenhar e recortar formas usando pontos
- 1. você tem um bloco (div);
- 2. escolhe pontos nele;
- 3. o CSS liga esses pontos;
- 4. tudo fora disso some..

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

Trapesio..
  20% 0%, -> topo esquerdo 
  80% 0%, -> topo direito 
  100% 100%, -> baixo direito 
  0% 100% -> baixo esquerdo 

Retangulo..
  0% 0%, -> topo esquerdo 
  100% 0%, -> topo direito 
  100% 100%, -> baixo direito 
  0% 100% -> baixo esquerdo 

Pentagono..
  50% 0%, -> topo 
  100% 38%, -> lado direito superior 
  82% 100%, -> lado direito inferior 
  18% 100%, -> lado esquerdo inferior 
  0% 38% -> lado esquerdo superior 

Paralelogramo..
  25% 0%, -> topo esquerdo deslocado 
  100% 0%, -> topo direito 
  75% 100%, -> baixo direito deslocado 
  0% 100% -> baixo esquerdo 

Loxango..
  50% 0%, -> topo 
  100% 50%, -> direita 
  50% 100%, -> baixo 
  0% 50% -> esquerda 

Hexagono..
  25% 0%, -> topo esquerdo 
  75% 0%, -> topo direito 
  100% 50%, -> meio direito 
  75% 100%, -> baixo direito 
  25% 100%, -> baixo esquerdo 
  0% 50% -> meio esquerdo 

Heptagono..
  50% 0%, -> topo 
  90% 20%, -> superior direito 
  100% 60%, -> meio direito 
  75% 100%, -> baixo direito 
  25% 100%, -> baixo esquerdo 
  0% 60%, -> meio esquerdo 
  10% 20% -> superior esquerdo 

Elipese..
  50% 30% at 50% 50% -> Define uma forma oval usando largura e 
  altura, centralizada no meio da figura.

Decagono..
  50% 0%, -> topo 
  79% 10%, -> topo direito 
  100% 35%, -> direita superior 
  100% 65%, -> direita inferior 
  79% 90%, -> baixo direito 
  50% 100%, -> baixo 
  21% 90%, -> baixo esquerdo 
  0% 65%, -> esquerda inferior 
  0% 35%, -> esquerda superior 
  21% 10% -> topo esquerdo 

Bisel..
  10% 0%, -> topo (canto cortado) 
  90% 0%, -> topo (canto cortado) 
  100% 10%, -> canto superior direito cortado 
  100% 90%, -> canto inferior direito cortado 
  90% 100%, -> base (canto cortado) 
  10% 100%, -> base (canto cortado) 
  0% 90%, -> canto inferior esquerdo cortado 
  0% 10% -> canto superior esquerdo cortado 