# Conway's Game of Life

Conway's Game of Life is a cellular automaton. Read more at https://en.wikipedia.org/wiki/Conway's_Game_of_Life

## Installing

This program is a ReactJS app. Run "yarn run build-prod" to build it, and then run index.html from the /docs folder.

## Limitations

The current version of this program assumes that when a cell reaches a boundary, it should "wrap around" and display on the other side of that boundary -- e.g. if a cell goes off the right edge, it reappears on the left edge. While researching Gosper's glider gun, I realized that this was not a proper implementation, because it results in the glider gun's "gliders" interfering and destroying the gun. In a future version, the wraparound feature will be removed.

## Author

Chris Snyder

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.