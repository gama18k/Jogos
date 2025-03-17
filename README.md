# Jogo de Adivinhação e Forca

Este repositório contém dois jogos simples implementados em Python: **Adivinhação** e **Forca**. O arquivo `jogos.py` é responsável por iniciar o jogo e permitir que o jogador escolha entre os dois.

## Jogos Disponíveis

1. **Adivinhação**: O jogador deve tentar adivinhar um número secreto gerado aleatoriamente, com um número limitado de tentativas, dependendo do nível de dificuldade.
   
2. **Forca**: O jogador deve adivinhar uma palavra secreta, acertando uma letra por vez. O jogador tem 7 tentativas para errar antes de ser "enforcado".

## Estrutura do Repositório

O repositório contém três arquivos principais:

- **`forca.py`**: Contém a lógica do jogo da Forca.
- **`adivinhacao.py`**: Contém a lógica do jogo de Adivinhação.
- **`jogos.py`**: O arquivo principal que inicia o jogo e permite que o jogador escolha entre "Forca" ou "Adivinhação".

## Como Rodar o Jogo

### Requisitos

- Python 3.x ou superior instalado no seu computador.

### Instruções

1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   cd SEU_REPOSITORIO
   ```

2. Execute o arquivo `jogos.py`:
   ```bash
   python jogos.py
   ```

3. Escolha qual jogo deseja jogar digitando o número correspondente:
   - Digite `1` para jogar **Forca**.
   - Digite `2` para jogar **Adivinhação**.

## Como Funciona

1. **Jogo da Forca**:
   - O jogo começa com a palavra secreta e o jogador deve tentar adivinhar uma letra de cada vez.
   - O jogador tem 7 tentativas antes de ser "enforcado".
   - Ao acertar todas as letras da palavra, o jogador vence.

2. **Jogo da Adivinhação**:
   - O jogador tenta adivinhar um número secreto entre 1 e 100.
   - O número de tentativas depende do nível de dificuldade escolhido:
     - Fácil: 20 tentativas.
     - Médio: 10 tentativas.
     - Difícil: 5 tentativas.
   - A cada tentativa, o jogo diz se o número é maior ou menor que o número secreto.
