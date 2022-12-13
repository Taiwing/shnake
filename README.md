# shnake

Snake game entirely implemented in shell.

<br />
<p align="center">
	<img src="https://github.com/Taiwing/shnake/blob/master/resources/ascii_snake.png?raw=true" alt="ascii snake" style="width: 50%;"/>
</p>

## Setup

No setup required. The only requirement is bash.

## Usage

```shell
# just run it
./shnake
```

> By default the game begins with a one block long snake ('#') and a cherry
> ('\*'). Start the game by chosing an initial direction with the arrow keys.

## Rules

Each cherry caugh makes the snake longer by 4 blocks. If the snake hits itself
or a wall the game ends. The score at the end is simply the length of the snake.

Use the arrow keys to move around and 'q' to quit the game.
