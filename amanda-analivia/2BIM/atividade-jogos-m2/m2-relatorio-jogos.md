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

# Jogo 1 - Dado Mágico

## Descrição

**Objetivo:**   
O objetivo deste aplicativo foi desenvolver um simulador digital de dados utilizando o MIT App Inventor, com foco no aprendizado de lógica de programação para dispositivos móveis. O projeto permitiu trabalhar a geração de números aleatórios, o uso de estruturas condicionais para alterar imagens dinamicamente, a integração de recursos multimídia (som e vibração) e a criação de interfaces com múltiplas telas e navegação entre elas.

**Funcionamento:**   
O aplicativo possui duas telas integradas. Ao clicar no botão *"Sortear"*, o sistema gera números aleatórios de 1 a 6, reproduz um efeito sonoro e faz o aparelho vibrar por 100 milissegundos. Em seguida, estruturas condicionais verificam os valores gerados e alteram as imagens para exibir a face correta dos dados.

Na segunda tela, acessada por um botão localizado no topo da tela principal, são exibidos dois dados simultaneamente. Ao realizar um novo sorteio, o aplicativo gera dois números aleatórios, atualiza as imagens correspondentes e calcula automaticamente a soma dos valores, exibindo o resultado ao usuário. Também há um botão para retornar à tela inicial, garantindo uma navegação simples e intuitiva.

**Modificações feitas diante do vídeo:**   
Foram realizadas personalizações na interface, incluindo novas imagens, alterações de cores e ajustes no tamanho dos botões para melhorar a aparência e a usabilidade do aplicativo.

Além disso, foi implementada uma segunda tela, recurso não presente no modelo original. Nela, o usuário pode visualizar dois dados ao mesmo tempo e acompanhar o resultado da soma dos valores sorteados. Já na tela principal, é exibido apenas um dado por vez, tornando as funcionalidades mais organizadas.


| Print da 1ª Tela do Design | Print da 2ª Tela do Design | Print da Tela dos Blocos |
| ---- | ---- | ---- |
| ![Design do Aplicativo](imagens/jogo1dado_screen1.png) | ![Design do Aplicativo](imagens/jogo1dado_screen2.png) | ![Blocos de programação](imagens/jogo1dado_blocos.png) |

--- 

# Jogo 2 - Adivinhe o Número

## Descrição

**Objetivo:**   

O objetivo deste aplicativo foi desenvolver um jogo interativo de desafio matemático utilizando o MIT App Inventor, com foco no aprendizado de lógica de programação para dispositivos móveis. O projeto permitiu trabalhar a criação e manipulação de variáveis globais, a geração de números aleatórios, o uso de estruturas condicionais para diferentes operações matemáticas (adição, subtração e multiplicação), além do controle de pontuação e da utilização de notificações e sons.

**Funcionamento:**   

O aplicativo funciona como um quiz de matemática. Ao iniciar, o sistema gera automaticamente dois números aleatórios entre 1 e 9999 e sorteia uma operação matemática. Dependendo do operador sorteado, é realizada uma adição, subtração ou multiplicação. No caso da subtração, o aplicativo garante que o maior número seja subtraído pelo menor, evitando resultados negativos.

O usuário deve calcular o resultado e digitá-lo no campo de resposta. Ao clicar no botão de verificação, o sistema compara o valor informado com o resultado correto. Em caso de acerto, o placar de acertos é atualizado, um som é reproduzido e uma mensagem de aviso é exibida. Em caso de erro, o placar de erros é incrementado, um som de erro é tocado, o dispositivo vibra e uma notificação informa a resposta correta. Após cada tentativa, o campo é limpo e uma nova conta é gerada automaticamente. O aplicativo também possui um botão para encerramento imediato.


**Modificações feitas diante do vídeo:**   
Foram realizadas alterações significativas em relação ao modelo original demonstrado em vídeo, visando a personalização e o aumento do desafio do jogo. A interface visual foi reestruturada através da alteração da paleta de cores, adotando tons de roxo, além da modificação no tamanho e fontes dos textos e da reorganização dos componentes visuais para tornar o aplicativo mais moderno e intuitivo.

Outra grande mudança ocorreu no aumento da complexidade matemática e da ordem de grandeza, visto que no projeto original do vídeo o sistema operava com números menores na casa das centenas, exibindo apenas três dígitos. Como modificação, a lógica dos blocos foi alterada para sortear números inteiros aleatórios de 1 a 9999, atualizando os campos de exibição para a casa dos milhares e elevando consideravelmente o nível de dificuldade dos cálculos.

Por fim, foi implementada uma melhoria na lógica do componente de notificação para o alerta de erro. Diferente do modelo base, que apenas notificava o erro em si, foi utilizado o bloco de texto para juntar informações, permitindo que o aplicativo agora exiba dinamicamente o valor correto da operação matemática junto com a mensagem de erro, garantindo que o usuário saiba imediatamente qual era o resultado exato e tornando o aplicativo muito mais didático.


| Print da Tela do Design | Print da Tela dos Blocos |
| ---- | ---- |
| ![Design do Aplicativo](imagens/jogo2adivinha_screen.png) | ![Blocos de programação](imagens/jogo2adivinha_blocos.png) |

--- 

