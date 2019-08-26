# Basic Pong HTML Game

This is a basic implementation of the Atari Pong game, but it's missing a few things intentionally and they're left as further exploration for the reader.

## Further Exploration

- Score
  - When a ball goes past a paddle, the othe player should score a point
- Mobile and touchscreen support
  - Allow the game to be scalled down to a phone size. See https://codepen.io/straker/pen/VazMaL
  - Support [touch controls](https://developer.mozilla.org/en-US/docs/Web/API/Touch_events)
- Ball trajectory
  - The ball should change trajectory based on where it hit the paddle. For example, if it hit the topmost part of the paddle it should have a sharp angle upward, whereas if it hit the direct middle of the paddle it should move completely flat towards the other payer.
  
## License

(CC0 1.0 Universal) You're free to use this game and code in any project, personal or commercial. There's no need to ask permission before using these. Giving attribution is not required, but appreciated.

## Other Basic Games

* [Snake](https://gist.github.com/straker/ff00b4b49669ad3dec890306d348adc4)
* [Breakout](https://gist.github.com/straker/98a2aed6a7686d26c04810f08bfaf66b)