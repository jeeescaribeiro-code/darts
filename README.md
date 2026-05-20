<div align="center">

```
██████╗  ██████╗ ███╗  ██╗████████╗ ██╗   ██╗ █████╗  ██████╗  █████╗  ██████╗
██╔══██╗██╔═══██╗████╗ ██║╚══██╔══╝ ██║   ██║██╔══██╗██╔════╝ ██╔══██╗██╔═══██╗
██████╔╝██║   ██║██╔██╗██║   ██║    ██║   ██║███████║██║      ███████║██║   ██║
██╔═══╝ ██║   ██║██║╚████║   ██║    ██║   ██║██╔══██║██║      ██╔══██║██║   ██║
██║     ╚██████╔╝██║ ╚███║   ██║    ╚██████╔╝██║  ██║╚██████╗ ██║  ██║╚██████╔╝
╚═╝      ╚═════╝ ╚═╝  ╚══╝   ╚═╝     ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝ ╚═════╝

██████╗ ███████╗    ██████╗  █████╗ ██████╗ ██████╗  ██████╗ ███████╗
██╔══██╗██╔════╝    ██╔══██╗██╔══██╗██╔══██╗██╔══██╗██╔═══██╗██╔════╝
██║  ██║█████╗      ██║  ██║███████║██████╔╝██║  ██║██║   ██║███████╗
██║  ██║██╔══╝      ██║  ██║██╔══██║██╔══██╗██║  ██║██║   ██║╚════██║
██████╔╝███████╗    ██████╔╝██║  ██║██║  ██║██████╔╝╚██████╔╝███████║
╚═════╝ ╚══════╝    ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚══════╝
```

**para quem é realmente ruim em matemática**

[![Abrir no navegador](https://img.shields.io/badge/🎯%20usar%20agora-FF4FBF?style=for-the-badge&logoColor=white)](https://jeeescaribeiro-code.github.io/darts/)
![HTML](https://img.shields.io/badge/HTML5-0A0A12?style=for-the-badge&logo=html5&logoColor=FF4FBF)
![CSS](https://img.shields.io/badge/CSS3-0A0A12?style=for-the-badge&logo=css3&logoColor=00F0FF)
![JavaScript](https://img.shields.io/badge/JavaScript-0A0A12?style=for-the-badge&logo=javascript&logoColor=B8FF3A)

</div>

---
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Syne&weight=700&size=22&pause=1000&color=FF4FBF&center=true&vCenter=true&width=500&lines=Contador+de+dardos+no+navegador;Sem+instala%C3%A7%C3%A3o%2C+sem+servidor;" alt="typing" />
</div>

## 🕹 use agora!
> **[jeeescaribeiro-code.github.io/darts](https://jeeescaribeiro-code.github.io/darts/)**

## ✦ como funciona

Configure a pontuação alvo (301, 501, o que quiser) e o número de rounds, adicione os jogadores e clique em **Iniciar**. A cada lançamento, digite os pontos marcados e o placar descontará automaticamente. Quem chegar a zero primeiro vence o round. Quem vencer mais rounds leva a partida.

O botão **↩ Undo** desfaz a última jogada a qualquer momento, inclusive se um round acabou de virar. Se a subtração deixaria o placar negativo, a jogada é bloqueada (**bust**) com alerta visual. Ao fim de cada partida, um banner de vitória aparece por 4 segundos e os rounds já resetam sozinhos para a próxima, sem precisar clicar em nada.

O **leaderboard** acumula vitórias de partida com medalhas 🥇🥈🥉 e persiste entre sessões. Se você fechar o navegador no meio de uma partida, ela retoma exatamente de onde parou na próxima vez que abrir.

---

## stack

Tudo em um único `index.html`; o estado é salvo via `localStorage`.

```
index.html   ← HTML + CSS + JS, tudo aqui
README.md    ← este arquivo
```

Para limpar o estado salvo:

```js
localStorage.removeItem('badmath_v2')
```

---

## 🎨 design

Tema escuro com paleta neon - pink `#FF4FBF`, cyan `#00F0FF`, lime `#B8FF3A`. Blobs animados no fundo, barra colorida por jogador, placar que muda de cor conforme a aproximação do zero, histórico dos últimos lances em chips inline.

---
