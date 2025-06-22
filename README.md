# 💻 Projetos em Linguagem C – Wyden

Bem-vindo ao repositório **Projetos C - Wyden**, uma coleção de códigos desenvolvidos durante os estudos de programação na **Faculdade Wyden**. Aqui você encontrará projetos voltados ao aprendizado dos conceitos fundamentais da linguagem **C**, como matrizes, loops, condicionais, funções e organização de código.

## 🚢 Batalha Naval

Este projeto simula o posicionamento de navios em um tabuleiro 10x10, com diferentes níveis:

- **Novato:** posicionamento de 2 navios (um horizontal e um vertical) com validações básicas.
- **Aventureiro:** posicionamento de 4 navios, incluindo diagonais.
- **Mestre:** adição de habilidades especiais com áreas de efeito (cone, cruz, octaedro) sobre o tabuleiro.

📌 *Conceitos abordados:* matrizes bidimensionais, estruturas condicionais, validações de coordenadas, visualização gráfica em ASCII.

---

## 🃏 Super Trunfo

Uma versão básica do famoso jogo **Super Trunfo**, com as seguintes fases:

- **Novato:** comparação simples entre cartas.
- **Aventureiro:** introdução de mais cartas e critérios.
- **Mestre:** lógica mais complexa, com leitura de atributos e decisão automática de vitória.

📌 *Conceitos abordados:* structs, comparação entre dados, entrada de dados, controle de fluxo.

---

## ♟️ Xadrez (Simples)

Implementação simplificada de lógica de movimentos de peças:

- **Novato:** movimentação básica de uma peça (ex: torre ou peão).
- **Aventureiro:** múltiplas peças e validação de caminhos.
- **Mestre:** simulação de jogadas com verificação de regras específicas.

📌 *Conceitos abordados:* vetores e matrizes, lógica condicional, tratamento de regras.

---

## 📁 Estrutura dos Arquivos

```bash
📦 PROJETOS_WYDEN
 ┣ 📂 .vscode
 ┃ ┣ 📜 launch.json
 ┃ ┗ 📜 tasks.json
 ┣ 📜 super_trunfo_logica
 ┣ 📂 batalha_naval
 ┃ ┣ 📜 batalha_aventureiro.c
 ┃ ┣ 📜 batalha_aventureiro.exe
 ┃ ┣ 📜 batalha_mestre.c
 ┃ ┣ 📜 batalha_mestre.exe
 ┃ ┣ 📜 batalha_novato.c
 ┃ ┗ 📜 batalha_novato.exe
 ┣ 📂 super_trunfo
 ┃ ┣ 📜 super_trunfo_aventureiro.c
 ┃ ┣ 📜 super_trunfo_aventureiro.exe
 ┃ ┣ 📜 super_trunfo_mestre.c
 ┃ ┣ 📜 super_trunfo_mestre.exe
 ┃ ┣ 📜 super_trunfo_novato.c
 ┃ ┗ 📜 super_trunfo_novato.exe
 ┣ 📂 xadrez
 ┃ ┣ 📜 xadrez_aventureiro.c
 ┃ ┣ 📜 xadrez_aventureiro.exe
 ┃ ┣ 📜 xadrez_mestre.c
 ┃ ┣ 📜 xadrez_mestre.exe
 ┃ ┣ 📜 xadrez_novato.c
 ┃ ┗ 📜 xadrez_novato.exe
 ┗ 📜 a.out

