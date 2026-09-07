1. As duas fases. Descreva cada uma em três linhas: o tema, o que o jogador faz nela, e uma
decisão de desenho que você tomou e o motivo.

A primeira tela fica a tela com os desing tropical com elementos de outros biomas. atravessa o mapa de maneira linear com uma decisao de seguir o caminho no meio do trajeto. Decisão dos 3 caminhos vcem pela dificuladade de cada um deles e conseguir adicionar a caverna e a sala secreta. Ficaria mais facil nessa tela.

A segunda tela usa elementos dos biomas de GlassLands. Atravassa o mapa pegando altura e pulandos por plataformas pequenas, uma montannha no final para ajudar a ganhar altura e mostrar os fundos das imagens se mexendo e funcionando como foi pedido na atividade.



2. O parallax. Quais valores de motion_scale você usou em cada camada, e como chegou neles. O
que mudou entre a primeira tentativa e a versão final?

Usei as primeiras menores com menos velocidade e fui aumentando consequentemente a cada imagem que passava. A decisao foi escolher um valor baixo e aumentar um numeroa mais. 



3. A área secreta. Onde está a pista, onde está a entrada, e por que você as separou desse jeito.

No mapa tem apenas uma placa e cercas brancas. Usando o que foi disponibilizado foi a unica maneira de conseguir deixar visivel. O motivo seria a facilidade de aplicar a sala nessa fase


4. A câmera. Qual das duas formas você escolheu, e o que perderia com a outra.

Uma cena criada apenas para a camera. Não cheguei a testar a outra. Fui na mais eficaz e melhor afinal o prazo para a atividade estava apertado para quem trabalha a semana toda. 



5. A transição. Explique, para alguém que não assistiu à aula, por que a troca de fase não pode
ser chamada direto na detecção da colisão.

pq colide com o mapa pois itens estao no mesmo layer.



6. O que travou. Aponte um momento em que algo não funcionou, o que você achou que era a
causa, o que era de verdade, e como descobriu. Se as duas coincidirem, diga isso — mas descreva
o caminho.

A transição de mapa. Achei que era o problema com a camera, o spaw da camera ficava em cima do collisionShape e imaginei que era o problema. Os layer estravam sendo gerados e isso fazia com que o jogador sempre teleportava. Deixei ele longe dos frames e deu certo.
