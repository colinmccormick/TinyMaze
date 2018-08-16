# TinyMaze

A very simple shell-based maze game. Useful for traing simple reinforcement learning algorithms. To play:

$ python TinyMaze.py <int maze_size>

To use in reinforcement learning:

```python
import TinyMaze

moves = ["a", "s", "w", "z"]
game = TinyMaze.TinyMazeEnv(maze_size)
status = game.step(moves[move_index])
```
