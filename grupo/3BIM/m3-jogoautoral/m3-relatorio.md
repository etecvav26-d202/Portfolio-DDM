# App Inventor: Jogo Autoral
**`Instituição:`**
ETEC Vasco Antônio Venchiarutti

**`Curso:`**
Informática para Internet

**`Turma:`**
2º ano D

**`Autores:`**
- [Alice Gimenez Siqueira](https://github.com/alice-gimenez)
- [Alice Rasmussen Rezende Alves](https://github.com/alicerez0703)
- [Amanda Neves Oliveira](https://github.com/amandanevoli)
- [Ana Lívia Takeyama Romanato](https://github.com/liviatakeyama)
- [Isabelli Dias da Silva](https://github.com/isabelbelli)

---

## Descrição

O aplicativo é um jogo de Ping Pong desenvolvido no MIT App Inventor, com uma temática inspirada em Pokémon. O jogador controla uma personagem localizada na parte inferior da tela, utilizando o movimento do celular para movimentá-la horizontalmente. Uma Pokébola se movimenta pela tela e deve ser rebatida pela personagem, enquanto os Pokémon funcionam como alvos que podem ser atingidos para aumentar a pontuação.


### 🎯 Objetivo

O objetivo do jogo é rebater a bola e atingir os Pokémon, acumulando pontos. O jogador começa com 3 vidas e deve tentar atingir os três alvos, que valem 10 pontos cada. Ao alcançar 30 pontos, o jogador vence a partida. Caso perca todas as vidas, o jogo termina.

### ⚙️ Funcionamento

O jogo utiliza o acelerômetro do celular para controlar a personagem. Ao inclinar o aparelho para a direita ou para a esquerda, a personagem se movimenta horizontalmente na mesa.

A bola é movimentada automaticamente por meio de um Timer, que atualiza sua posição a cada intervalo de tempo. Quando a bola atinge as laterais da mesa, sua direção horizontal é invertida, fazendo com que ela volte para o outro lado.

Quando a bola atinge a personagem, sua direção vertical também é alterada, fazendo com que ela seja rebatida para cima. Quando a bola atinge um dos Pokémon, o jogador recebe 10 pontos, o Pokémon desaparece e a bola muda sua direção.

O jogo possui um sistema de vidas e pontuação. Ao deixar a bola passar pela personagem, o jogador perde uma vida e a bola retorna à posição inicial. Quando todos os Pokémon são atingidos e o jogador chega a 30 pontos, aparece uma mensagem indicando a vitória. Se o jogador perder as vidas disponíveis, aparece uma mensagem de Game Over e é possível reiniciar a partida.

## Print das Telas do Design e dos Blocos

| Print da tela do Design | Print da tela dos Blocos |
|------|------|
| ![Desing do aplicativo](img/design_screen1.png) | ![Blocos de programação](img/blocos_screen1.png) |
