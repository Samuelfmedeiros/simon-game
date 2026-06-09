# Simon Game 🎮

Um jogo clássico de memorização de sequência de cores, implementado como uma aplicação React standalone (via CDN).

## Sobre o Jogo

O **Simon Game** é um jogo eletrônico clássico lançado nos anos 1970. O objetivo é simples: o jogador deve memorizar e repetir uma sequência de cores que aumenta progressivamente a cada rodada.

### Como Jogar

1. Clique em **▶ Iniciar Jogo** para começar.
2. Observe atentamente a sequência de cores que o jogo irá mostrar 👀
3. Repita a sequência clicando nos botões nas mesma ordem 🎯
4. A cada acerto, um novo passo é adicionado à sequência, tornando-a mais longa.
5. Se você errar, o jogo acaba e sua pontuação é exibida 💀
6. Clique em **Tentar Novamente** para começar uma nova partida.

### Cores

| Botão    | Cor       |
|----------|-----------|
| Vermelho | `#ef4444` |
| Verde    | `#22c55e` |
| Azul     | `#3b82f6` |
| Amarelo  | `#f59e0b` |

## Como Executar

Basta abrir o arquivo `index.html` em qualquer navegador moderno. O React 18 e o Babel são carregados via CDN, então nenhuma instalação ou build é necessária.

```
# Clone o repositório
git clone https://github.com/Samuelfmedeiros/simon-game.git

# Abra o arquivo
cd simon-game
open index.html   # ou clique duas vezes no arquivo
```

## Stack

- **React 18** — via CDN (umd)
- **Babel Standalone** — transpilação JSX no navegador
- **CSS puro** — tema escuro, sem dependências externas

## Licença

MIT — sinta-se à vontade para usar, modificar e compartilhar.
