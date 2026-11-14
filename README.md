# Word Hunt

A family word-guessing game. Play solo, or with friends on your phones: everyone gets the same words, with a timer and points.

- **Solo:** Easy (4 letters), Normal and Hard. Fewer guesses earn more points.
- **Live:** everyone plays each word at the same time; the host starts each word.
- **Async:** everyone plays the same words whenever they like before the game closes.

The game is a single static page (`index.html` + `words.js`). Multiplayer rooms run through Supabase functions (`wordhunt_*`); the secret words stay on the server, and phones only get back the colors for each guess.
