# Hexagonal 2048

- This project represents "2048" game on hexagonal canvas. 
- Also this project has possibility to select a game level via radius option.
- To play this game you should use your keyboard keys (q,w,e,a,s,d).
- Live deployment on [github pages](https://thelastdance.github.io/Hexagon_2048/)
- used technologies/libraries: react, sass, react-router-dom, react-hex-grid, uniqid.
- If you want to run this game from private local server use hostname and port options, if not just leave this fields as it is.


### Directions and Keys

You have 6 keyboard keys (Latin lower case letters) for 6 existing directions:

| Direction                 | Keyboard key |
| ------------------------- | :----------: |
| north (top)               |      w       |
| north-east (top-right)    |      e       |
| north-west (top-left)     |      q       |
| south (bottom)            |      s       |
| south-east (bottom-right) |      d       |
| south-west (bottom-left)  |      a       |

After pressing any of the listed keys, all your numbers should be shifted in the chosen direction.

### Shifting rules

Shifting works according to common [2048](https://play2048.co/) rules [EN](<https://en.wikipedia.org/wiki/2048_(video_game)>)) taking into account
appropriate hexagonal direction.

| before shift → |   after |
| -------------: | ------: |
|            2 2 |       4 |
|          2 2 2 |     2 4 |
|          2 2 4 |     4 4 |
|          4 2 2 |     4 4 |
|        2 4 2 4 | 2 4 2 4 |
|        2 2 4 4 |     4 8 |



