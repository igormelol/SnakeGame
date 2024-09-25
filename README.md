## Jogo da Cobrinha

Descrição:
Este é um jogo clássico da cobrinha, implementado em JavaScript utilizando o canvas HTML5. O jogador controla uma cobra usando as setas do teclado, com o objetivo de comer a comida e crescer, evitando colidir com o próprio corpo.

Tecnologias:

Canvas HTML5
JavaScript

Como Jogar:

Abra o arquivo index.html em um navegador web.
Use as setas do teclado para controlar os movimentos da cobra.
A cobra crescerá a cada pedaço de comida que comer.
Evite colidir com o próprio corpo.

Estrutura do Código:

HTML: Define o elemento canvas.

JavaScript:
window.onload: Inicializa o jogo.
document.addEventListener("keydown"): Captura as teclas pressionadas.
setInterval(jogo, 100): Atualiza o estado do jogo a cada 100 milissegundos.

Função jogo():
Atualiza a posição da cobra com base na velocidade.
Verifica colisões com as paredes e com o próprio corpo.
Desenha a cobra, a comida e o fundo.
Gera nova comida quando a cobra a come.

Lógica do Jogo:

A cobra é representada por um array de objetos, cada um com uma coordenada x e y.
O movimento da cobra é controlado pelas variáveis velX e velY.
A cobra cresce quando come a comida, aumentando o valor da variável tam.
A comida é gerada aleatoriamente dentro dos limites do canvas.

Melhorias Futuras:

Adicionar um sistema de pontuação.
Implementar diferentes modos de jogo ou níveis de dificuldade.
Melhorar os gráficos e animações do jogo.


Desenvolvedores: Entender o código e fazer modificações.
Usuários: Saber como jogar e o que esperar do jogo.

Tradução de Termos Técnicos:

Canvas: Uma área retangular onde se pode desenhar gráficos usando JavaScript.
JavaScript: Uma linguagem de programação usada para criar interatividade em páginas web.
Array: Uma estrutura de dados que armazena uma coleção de valores.


Igor M. L  2024
