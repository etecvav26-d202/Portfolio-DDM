# Relatório dos Jogos

**`Instituição:`**
ETEC Vasco Antônio Venchiarutti

**`Curso:`**
Informática para Internet

**`Turma:`**
2º ano D

**`Autores:`**
- [Amanda Neves Oliveira](https://github.com/amandanevoli)
- [Ana Lívia Takeyama Romanato](https://github.com/liviatakeyama)

---

# Jogo 1 - Magic Ball

## Descrição

**Objetivo:**   

O objetivo do projeto é criar um jogo no MIT App Inventor utilizando o acelerômetro do celular para controlar uma bola. O jogador deve inclinar o aparelho para movimentar a bola e tentar acertar o buraco, acumulando pontos e diminuindo a quantidade de bolas restantes. O jogo também possui um limite de tempo, tornando a partida mais desafiadora.

**Funcionamento:**   

A bola é movimentada pelo acelerômetro através dos eixos X e Y, de acordo com a inclinação do celular. Ela possui uma sombra para deixar o movimento mais parecido com uma mesa. Também foi programado um sistema para que a bola, ao atingir uma borda, apareça do outro lado do Canvas. O buraco muda de posição durante o jogo e, quando a bola colide com ele, ocorre o registro do acerto e a atualização das bolas restantes

**Modificações feitas:**   

A partir do material fornecido, foram feitas modificações principalmente no design e na organização do jogo. Foram utilizadas novas imagens, cores e uma organização diferente dos componentes da tela. Também foram realizados ajustes nos blocos para controlar a pontuação, as bolas restantes, o tempo e a velocidade do buraco. Essas alterações foram feitas para deixar o jogo mais personalizado e melhorar sua jogabilidade, mantendo a ideia principal apresentada no material.

| Print da Tela do Design | Print da Tela dos Blocos |
| ---- | ---- |
| ![Design do Aplicativo](img/jogo1_screen1_design.png) | ![Blocos de programação](img/jogo1_screen1_blocks.png) |

---

# Jogo 2 - Bilharzinho

## Descrição

**Objetivo:**   

O objetivo das modificações foi melhorar o jogo de bilhar apresentado no material, deixando-o mais completo, divertido e desafiador, além de tornar a experiência mais próxima de um jogo de verdade. A versão original trabalha conceitos como movimento da bola, colisão com as bordas, gravidade artificial e caçapas.

**Funcionamento:**   

O jogador realiza uma tacada arrastando a bola e soltando na direção desejada. A bola se movimenta pela mesa, rebate nas bordas e diminui sua velocidade gradualmente até parar, simulando o atrito de uma mesa de bilhar. Quando a bola colide com uma das seis caçapas, ela para, um som é reproduzido, a bola retorna ao centro e o jogador recebe um ponto.

**Modificações feitas:**   

A partir do material fornecido, foram adicionadas diversas melhorias. Foi criada uma interface personalizada com uma nova imagem de mesa, além de sistema de pontuação, três vidas e cronômetro. Também foram adicionados níveis de dificuldade. Foram criadas telas de redirecionamento assim que o jogador ganha ou perde a partida. As caçapas passaram a funcionar como áreas de colisão invisíveis, deixando a aparência da mesa mais limpa. Também foi corrigido o comportamento da bola ao entrar na caçapa, fazendo com que ela pare completamente antes de retornar ao centro, evitando que continue se movimentando.

