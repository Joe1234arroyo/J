# Basic Pong HTML Game

This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally and they're left as further exploration for the reader.

<img width="300" alt="image" src="https://user-images.githubusercontent.com/2433219/94984423-03b57400-0509-11eb-91b0-974280cec0a2.png">

## Further Exploration

- Score
  - When a ball goes past a paddle, the other player should score a point. Use [context.fillText()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/fillText) to display the score to the screen
- Mobile and touchscreen support
  - Allow the game to be scalled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.
  
**Important note:** I will answer questions about the code but will not add more features or answer questions about adding more features. This series is meant to give a basic outline of the game but nothing more.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

## Other Basic Games

- [Snake](https://gist.github.com/straker/ff00b4b49669ad3dec890306d348adc4)
- [Breakout](https://gist.github.com/straker/98a2aed6a7686d26c04810f08bfaf66b)
- [Tetris](https://gist.github.com/straker/3c98304f8a6a9174efd8292800891ea1)
- [Bomberman](https://gist.github.com/straker/769fb461e066147ea16ac2cb9463beae)
- [Frogger](https://gist.github.com/straker/82a4368849cbd441b05bd6a044f2b2d3)

## Support

Basic HTML Games are made possible by users like you. When you become a [Patron](https://www.patreon.com/straker), you get access to behind the scenes development logs, the ability to vote on which games I work on next, and early access to the next Basic HTML Game.

### Top Patrons

- Innkeeper Games
- Karar Al-Remahy