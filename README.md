# Prova2
Prova Trabalho  - POO - Mirla - Femc Facit

Para o Este trabalho foi Utilizado JavaScript e HTML/CSS.

ESTRUTURA DO TRABALHO
  - Crie um programa para a estrutura de um jogo de xadrez: Estrutura do tabuleiro, organização das
  peças brancas e pretas, busca de movimentos de cada peça, implementação de cada regra (exemplos: primeira saída do
  peão pode-se andar duas ou uma casa, a escolha do usuário, o peão não pode andar para trás, a não ser que seja para
  derrubar uma pessoa, etc.), a vez e o tempo de cada usuário, o processo do xeque e xeque-mate. Pense nos módulos de
  desenvolvimento dos dois jogadores, assim como nos métodos referentes a cada peça, regra e movimento. Pense na
  contagem das peças e na recontagem, quando uma peça é retirada da jogada. Pense na liberação do espaço
  quadriculado com uma peça a menos. Nos movimentos possíveis de cada peça, mediante aos espaços ocupados.
  

INTRODUÇÃO

As Regras do Xadrez da FIDE regulamentam o jogo no tabuleiro.

As Regras do Xadrez têm duas partes: 1. Regras Básicas de Jogo e 2. Regras de Competição.

O texto em língua inglesa é a versão autêntica das Regras do Xadrez (a qual foi adaptada no 87º Congresso de Baku, Azerbaijão e ‘FIDE Presidential Board 2017’ em Atenas) entrando em vigor em 1º de julho de 2017.

Nestas Regras, as palavras "ele", "lhe" e "seu" incluem "ela" e "sua".

PREFÁCIO

As Regras do Xadrez não podem abranger todas as situações possíveis que podem surgir durante uma partida, nem podem regular todas as questões administrativas.

Nos casos que não estejam precisamente regulamentados por um Artigo das Leis, deve ser possível alcançar-se uma decisão correta, analisando situações análogas reguladas nas Regras.

As Regras pressupõem que os árbitros têm a necessária competência, capacidade de julgamento e absoluta objetividade.

Uma regra muito detalhada pode privar o árbitro de sua liberdade de julgamento e assim impedi-lo de encontrar uma solução para um problema ditado pela justiça, lógica e fatores especiais.

A FIDE apela a todos os enxadristas e federações que aceitem este ponto de vista.

A condição necessária para uma partida ter rating calculado pela FIDE é que o torneio deve ser jogado de acordo com as Regras do Xadrez da FIDE.

Recomenda-se que mesmo os jogos competitivos não válidos para rating FIDE sejam jogados de acordo com as Regras do Xadrez da FIDE.

As federações filiadas podem solicitar à FIDE que se pronuncie sobre questões relativas às Regras do Xadrez.
Tradução para a língua escrita no Brasil foi realizada pelo AI Antonio Bento.

​ARTIGO 1: A NATUREZA E OBJETIVOS DO JOGO DE XADREZ 

1.1 O jogo de xadrez é disputado entre dois oponentes que movem suas peças sobre um tabuleiro quadrado denominado 'tabuleiro de xadrez'.

1.2 O jogador com as peças de cor clara (Brancas) faz o primeiro lance, em seguida os jogadores movem alternadamente, com o jogador com as peças de cor escura (Pretas) executando o próximo lance.

1.3 Diz-se que um jogador 'tem a vez de jogar', quando a jogada do seu oponente tiver sido 'efetuada'.

​1.4 O objetivo de cada jogador é colocar o rei do oponente 'sob ataque' de tal forma que o oponente não tenha lance legal.
1.4.1 O jogador que alcançar esse objetivo diz-se que deu xeque-mate no rei do adversário e venceu a partida. Não é permitido deixar ou colocar o seu próprio rei sob ataque, nem capturar o rei do oponente.
1.4.2 O oponente cujo rei sofreu xeque-mate perdeu a partida.

​1.5 A partida está empatada se resultar numa posição em que nenhum dos jogadores tem possibilidade de dar xeque-mate no rei do oponente (veja Artigo 5.2.2).
