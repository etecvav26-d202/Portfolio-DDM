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
O objetivo deste aplicativo foi desenvolver um simulador digital interativo de dados utilizando o MIT App Inventor, com foco no aprendizado de lógica de programação para dispositivos móveis. O projeto teve como finalidade prática compreender a manipulação de variáveis e propriedades dinâmicas, como a geração de números inteiros aleatórios (randomização), o uso de estruturas condicionais encadeadas (`se... então`) para alteração de componentes visuais (Imagens), e a integração de recursos multimídia (componentes de `Som` e vibração do dispositivo). Além disso, o aplicativo permitiu exercitar a criação de interfaces com múltiplas telas e a navegação entre elas.

**Funcionamento:**   
O aplicativo é composto por duas telas de design integradas. Ao interagir com o botão *"Sortear"*, o sistema gera simultaneamente dois números inteiros aleatórios no intervalo de 1 a 6, armazenando-os em rótulos de texto. No mesmo instante, os componentes de multimídia são acionados, reproduzindo um efeito sonoro e fazendo o aparelho vibrar por 100 milissegundos.

Na sequência, uma estrutura de blocos condicionais verifica o valor gerado para cada dado e altera dinamicamente a propriedade da imagem correspondente para exibir a face correta do dado. Por fim, ao clicar no botão que redireciona o usuário para a segunda tela do aplicativo, presente no topo da tela, ao clicar no botão *"Sortear"*, é realizado a operação matemática de soma entre os dois valores sorteados e exibido o resultado. O usuário também pode utilizar o botão superior, na mesma página, para navegar de volta à tela inicial, garantindo a fluidez e a usabilidade do aplicativo.

**Modificações feitas diante do vídeo:**   
Foram realizadas algumas modificações em relação ao modelo original apresentado em vídeo. A interface foi personalizada com a identidade visual do projeto, incluindo a adição de novas imagens e alterações estéticas no botão, como a mudança de cor e ajuste de tamanho para melhorar a usabilidade.

Também foi implementado um recurso avançado aprendido em aulas anteriores: a inserção de uma nova tela para segmentar as funções do aplicativo. Nessa tela secundária (acessada através do botão localizado no topo da tela principal), o usuário visualiza dois dados simultaneamente. Ao clicar no botão inferior *("Sortear")*, o aplicativo gera dois números inteiros aleatórios no intervalo de 1 a 6, altera as imagens correspondentes em tempo real e realiza a soma automática dos valores, exibindo o resultado logo abaixo para o usuário. Já na tela principal, é exibido apenas um dado por vez. 

| Print da 1ª Tela do Design | Print da 2ª Tela do Design | Print da Tela dos Blocos |
| ---- | ---- | ---- |
| ![Design do Aplicativo](imagens/jogo1dado_screen1.png) | ![Design do Aplicativo](imagens/jogo1dado_screen2.png) | ![Blocos de programação](imagens/jogo1dado_blocos.png) |

--- 

# Jogo 2 - Adivinhe o Número

## Descrição

**Objetivo:**   
O objetivo deste aplicativo foi desenvolver um jogo interativo de desafio matemático utilizando o MIT App Inventor. O projeto teve como finalidade prática aprofundar os conhecimentos em lógica de programação mobile, focando na criação e manipulação de variáveis globais, geração de valores aleatórios de grande escala, e no uso de estruturas condicionais aninhadas (`se... então... senão`) para gerenciar diferentes operações matemáticas (adição, subtração e multiplicação). Além disso, buscou-se trabalhar com o armazenamento e atualização em tempo real de pontuações (placar de acertos e erros) e a integração de notificações para o usuário.

**Funcionamento:**   


**Modificações feitas diante do vídeo:**   

| Print da Tela do Design | Print da Tela dos Blocos |
| ---- | ---- |
| ![Design do Aplicativo](imagens/jogo2adivinha_screen.png) | ![Blocos de programação](imagens/jogo2adivinha_blocos.png) |

--- 

