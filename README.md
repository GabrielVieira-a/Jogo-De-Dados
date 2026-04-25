# 🎲 Dicee Game

Uma aplicação web simples que simula o lançamento de dois dados para dois jogadores. Ao atualizar a página, os dados são rolados automaticamente e o vencedor é exibido na tela.

---

## 🚀 Funcionalidades

* Geração de números aleatórios para simular dados 🎲
* Atualização dinâmica das imagens dos dados
* Comparação entre os jogadores
* Exibição do vencedor ou empate

---

## 🧠 Como funciona

1. A aplicação gera dois números aleatórios entre **1 e 6**:

   ```javascript
   Math.floor(Math.random() * 6) + 1;
   ```

2. Cada número corresponde a uma imagem de dado:

   * `dice1.png` até `dice6.png`

3. As funções:

   * `dado1()` → atualiza o dado do Player 1
   * `dado2()` → atualiza o dado do Player 2
   * `vencedor()` → compara os valores e mostra o resultado

4. O resultado aparece no título (`<h1>`):

   * "Player 1 Wins!"
   * "Player 2 Wins!"
   * "Draw!"

---

## 🗂️ Estrutura do Projeto

```
Dicee/
│
├── index.html
├── styles.css
├── script.js
└── images/
    ├── dice1.png
    ├── dice2.png
    ├── dice3.png
    ├── dice4.png
    ├── dice5.png
    └── dice6.png
```

---

## 💻 Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript (DOM e funções básicas)

---

## ▶️ Como executar

1. Baixe ou clone o projeto
2. Abra o arquivo `index.html` no navegador
3. Atualize a página (F5) para rolar os dados 🎲

---

## 📌 Observações

* O jogo é atualizado automaticamente ao recarregar a página
* Não há interação por botão (pode ser uma melhoria futura)

---

## 💡 Possíveis melhorias

* Adicionar botão "Roll Dice"
* Animação ao rolar os dados
* Placar de vitórias
* Melhorar responsividade

---

## 📄 Licença

Projeto desenvolvido para fins de revisão e aprendizado.
