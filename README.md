# jokenpo-yu-gi-oh


Este é um jogo inspirado no **Jo-Ken-Po (Pedra, Papel e Tesoura)**, mas com cartas do universo de **Yu-Gi-Oh!**. O jogo permite ao jogador escolher uma carta para competir contra uma carta do computador. A cada duelo, o jogo exibe o vencedor e atualiza a pontuação. Além disso, uma música tema e um vídeo de fundo inspirados no universo de Yu-Gi-Oh! são reproduzidos durante o jogo.

## Funcionalidades

- **Cartas interativas**: O jogador pode selecionar uma carta clicando nela, e uma carta aleatória é escolhida pelo computador.
- **Duelos**: O jogador compete contra o computador no estilo Jo-Ken-Po (Pedra, Papel e Tesoura).
- **Pontuação**: A pontuação do jogador e do computador é exibida e atualizada após cada duelo.
- **Música de fundo**: Uma música tema de Yu-Gi-Oh! (Egyptian Duel) toca durante o jogo.
- **Vídeo de fundo**: Um vídeo com tema do jogo é reproduzido enquanto o jogo está em andamento.
- **Animação e efeitos sonoros**: Durante o duelo, são executados efeitos sonoros para indicar o resultado (Vitória, Derrota ou Empate).

## Como usar

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/seu-usuario/yu-gi-oh-jokenpo.git
    ```

2. Abra o arquivo `index.html` em seu navegador para começar a jogar.

## Estrutura de arquivos

O projeto possui os seguintes arquivos principais:

- `index.html`: A estrutura HTML da página, com a interface do jogo.
- `src/styles/main.css`: O estilo principal do jogo, incluindo a interface de cartas e pontuação.
- `src/styles/button.css`: Estilos específicos para os botões do jogo.
- `src/styles/containers_and_frames.css`: Estilos para o layout das caixas e frames das cartas.
- `src/styles/reset.css`: Reset de estilos para garantir uma aparência consistente.
- `src/assets/audios/egyptian_duel.mp3`: Música de fundo (tema do jogo).
- `src/assets/icons/`: Ícones e imagens das cartas.
- `src/scripts/engine.js`: A lógica do jogo, incluindo a funcionalidade de duelo, seleção de cartas e atualização da pontuação.

## Tecnologias utilizadas

- **HTML**: Estrutura da página e interface do jogo.
- **CSS**: Estilos da interface, incluindo as cartas, pontuação e animações.
- **JavaScript**: Lógica do jogo, com controle das cartas, resultado do duelo e atualização de pontuação.

## Como funciona

### HTML
O HTML define a estrutura do jogo, com uma área para exibir as cartas do jogador e do computador, a pontuação e um vídeo e música de fundo.

### CSS
O CSS estiliza a interface do jogo, com detalhes sobre a disposição das cartas, botões e a exibição do vídeo de fundo.

### JavaScript
O JavaScript gerencia a lógica do jogo, como a escolha aleatória das cartas, os duelos entre o jogador e o computador, a verificação dos resultados (vitória, derrota ou empate) e a atualização da pontuação. Além disso, o jogo usa áudio e animações para melhorar a experiência do usuário.

#### Funções principais:
- `getRandomCardId`: Retorna um ID aleatório de carta para o computador.
- `createCardImage`: Cria e exibe as cartas do jogador e do computador.
- `setCardsField`: Exibe as cartas no campo de jogo e verifica o resultado do duelo.
- `checkDuelResults`: Compara as cartas do jogador e do computador para determinar o vencedor.
- `updateScore`: Atualiza a pontuação na interface.
- `playAudio`: Reproduz o áudio correspondente ao resultado do duelo.
- `init`: Inicializa o jogo, desenhando as cartas e tocando a música de fundo.

## Exemplo de uso

1. Clique nas cartas para selecionar uma carta do jogador.
2. O computador escolherá uma carta aleatória.
3. O resultado do duelo será exibido (Vitória, Derrota ou Empate) e a pontuação será atualizada.
4. Clique no botão "GANHOU" para reiniciar o duelo.

## Contribuição

Sinta-se à vontade para contribuir com melhorias no projeto, correções ou novos recursos! Basta abrir uma **issue** ou enviar um **pull request**.
