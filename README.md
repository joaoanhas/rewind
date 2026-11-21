# Rewind

**English** · [Português](#português)

A party game for the browser: one player records a word, the other hears it backwards, imitates the sound, and when that imitation is reversed the original word comes out (or not).

**Play:** https://joaoanhas.github.io/rewind/

## How to play

1. Player 1 sees a random secret word and records it (up to 10 seconds).
2. Player 2 plays the recording **reversed**, imitates exactly what they hear and records it.
3. Play player 2's recording reversed. If the imitation was good, the original word appears.
4. Player 2 says their guess, then reveal the word and score the point.

## Features

- **Free play** for two players, swapping roles each round.
- **Tournament** for 2 to 16 players: random draw, knockout bracket, and automatic byes when the number of players doesn't fill the bracket. Each match can be 1 game, best of 3 or best of 5.
- Playback at **1x, 0.75x and 0.5x**.
- Limit on how many times player 1's recording can be played backwards (3, 5 by default, 10 or unlimited), and a confirmation before playing it forwards, since that gives the word away.
- **English and Portuguese** interface and word lists (PT / EN switch at the top).
- Voice only: the app asks for the microphone, never the camera.
- A single `index.html` with no backend or build step. The tournament is saved in the browser, so reloading the page keeps it.

## Running it

Open `index.html` in a browser, or host it on any static host (GitHub Pages, Netlify…). The microphone needs `https` or `localhost`.

---

## Português

Jogo de festa para o browser: um jogador grava uma palavra, o outro ouve-a ao contrário, imita o som e, ao inverter essa imitação, a palavra original aparece (ou não).

**Jogar:** https://joaoanhas.github.io/rewind/

- **Partida livre** para dois jogadores, ou **torneio** de 2 a 16 jogadores com eliminatórias, passagem direta automática e jogos de 1 partida, melhor de 3 ou melhor de 5.
- Reprodução a 1x, 0,75x e 0,5x.
- Interface e palavras em português e inglês.
- Só usa o microfone, nunca a câmara.
