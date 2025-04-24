# ♟️ Simulador de Movimento de Peças de Xadrez — em C

Este projeto simula os movimentos básicos de três peças do xadrez (Torre, Bispo e Rainha) utilizando estruturas de repetição em linguagem C. Cada peça utiliza um tipo diferente de loop para ilustrar seu deslocamento no tabuleiro.

## 🚀 Funcionalidades

- Simulação do movimento da **Torre** (5 casas para a direita) com `for`
- Simulação do movimento do **Bispo** (5 casas na diagonal para cima e à direita) com `while`
- Simulação do movimento da **Rainha** (8 casas para a esquerda) com `do-while`
- Impressão no console da direção do movimento a cada casa percorrida

## 📄 Estrutura do Código

- `for`: Torre  
  Exibe `"Direita"` cinco vezes

- `while`: Bispo  
  Exibe `"Cima Direita"` cinco vezes

- `do-while`: Rainha  
  Exibe `"Esquerda"` oito vezes

## 📷 Exemplo de saída

Movimento da Torre (5 casas para a direita): Direita Direita Direita Direita Direita

Movimento do Bispo (5 casas na diagonal cima-direita): Cima Direita Cima Direita Cima Direita Cima Direita Cima Direita

Movimento da Rainha (8 casas para a esquerda): Esquerda Esquerda Esquerda Esquerda Esquerda Esquerda Esquerda Esquerda

## 🛠️ Como compilar

Se estiver usando o terminal:

```bash
gcc movimento_xadrez.c -o xadrez
./xadrez

Se estiver usando o Replit ou outro compilador online, apenas cole o código e execute!
