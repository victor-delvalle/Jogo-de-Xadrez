# Jogo de Xadrez no Console

Este é um jogo de xadrez desenvolvido em **C#** utilizando o **.NET Framework** para execução no console. O projeto implementa as regras básicas do xadrez, proporcionando uma experiência educativa e funcional.

## 🚀 Funcionalidades

- **Tabuleiro 8x8**: Representado no console.
- **Movimentos válidos**: Implementados para todas as peças (rei, dama, torre, bispo, cavalo e peão).
- **Troca de turnos**: Alternância entre jogadores.
- **Validação de movimentos**: Verificação de jogadas permitidas.
- **Detecção de xeque**: Validações para estado de xeque.

## 🛠️ Tecnologias Utilizadas

- **C#**: Linguagem de programação utilizada.
- **.NET Framework**: Framework usado para o desenvolvimento.

## 📂 Estrutura do Projeto

O projeto está organizado nos seguintes namespaces:

- **`tabuleiro`**: Responsável por representar o tabuleiro e a peça base.
- **`xadrez`**: Implementação específica das regras do jogo de xadrez.
- **`Program.cs`**: Arquivo principal que executa o jogo.

## 📖 Regras Implementadas

- Movimentos válidos para todas as peças:
  - **Rei**: Move-se 1 casa em qualquer direção.
  - **Dama**: Move-se ilimitadamente nas direções horizontal, vertical e diagonal.
  - **Torre**: Move-se ilimitadamente nas direções horizontal e vertical.
  - **Bispo**: Move-se ilimitadamente na diagonal.
  - **Cavalo**: Move-se em formato de "L".
  - **Peão**: Movimentos restritos e captura específica.
- Verificação de **xeque**: Identificação se o rei de um jogador está sob ataque.
- Alternância de jogadores: Troca entre **brancas** e **pretas**.

## 📷 Exemplo no Console

```text
8  T  C  B  D  R  B  C  T
7  p  p  p  p  p  p  p  p
6  .  .  .  .  .  .  .  .
5  .  .  .  .  .  .  .  .
4  .  .  .  .  .  .  .  .
3  .  .  .  .  .  .  .  .
2  P  P  P  P  P  P  P  P
1  T  C  B  D  R  B  C  T
   a  b  c  d  e  f  g  h
