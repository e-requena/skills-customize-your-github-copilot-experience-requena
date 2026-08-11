# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Construa um jogo de Hangman (forca) em linha de comando usando Python para praticar manipulação de strings, laços, condicionais e entrada do usuário.

## 📝 Tasks

### 🛠️ Game Implementation

#### Description

Implemente o jogo Hangman jogável a partir do terminal. O programa deve escolher uma palavra secreta de uma lista pré-definida, aceitar palpites de letras do jogador e mostrar o progresso até que o jogador vença ou esgote as tentativas.

#### Requirements
Completed program should:

- Randomly select a secret word from a predefined list.
- Prompt the player for single-letter guesses and validate input (ignore repeated guesses, non-letters, or multi-character input).
- Display current progress using underscores and revealed letters (ex.: `_ a _ g a n`).
- Track and display incorrect guesses remaining and the letters already guessed.
- End the round with a clear win or lose message and reveal the secret word when the player loses.
- Provide a `main()` entry point so the script can be run directly.

#### Example session

```
Word: _ _ _ _ _ _
Guess a letter: a
Correct! Current: _ a _ _ _ _
Attempts remaining: 6
```

