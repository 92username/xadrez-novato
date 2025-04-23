# Simulação de Movimentação de Peças de Xadrez em C ♟️

Este projeto foi desenvolvido como parte do desafio da disciplina de Programação em C, com foco no uso de estruturas de repetição (`for`, `while` e `do-while`) para simular movimentos de peças do jogo de xadrez.

## Universidade Estácio de Sá

Projeto desenvolvido para a disciplina Introdução à Programação de Computadores.
Curso Engenharia de Software.

## Objetivo

Simular os movimentos das peças **Torre**, **Bispo** e **Rainha**, utilizando diferentes estruturas de repetição, conforme o nível novato do desafio proposto.

## Conteúdo

Arquivo principal:
- `xadrez-novato.c`: código-fonte com a simulação dos movimentos das peças.

## Peças e Lógica Utilizada

| Peça   | Movimento Simulado               | Estrutura Usada |
|--------|----------------------------------|------------------|
| Torre  | 5 casas para a direita           | `for`           |
| Bispo  | 5 casas na diagonal (cima/direita)| `while`        |
| Rainha | 8 casas para a esquerda          | `do-while`      |

Cada movimento é impresso no terminal com `printf()` a cada casa percorrida.

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/92username/xadrez-novato.git
   cd xadrez-novato
   ```

2. Compile o programa:
   ```bash
   gcc xadrez-novato.c -o xadrez
   ```

3. Execute:
   ```bash
   ./xadrez
   ```

## Requisitos

- Linguagem: C
- Compilador: GCC (ou compatível)

## Aprendizado

Desenvolve o pensamento lógico e o uso de estruturas fundamentais da programação, sendo ideal para iniciantes que estão aprendendo a utilizar **loops** em C.

## 📎 Licença

Projeto acadêmico. Uso livre para fins educacionais.  


