# pixel-grove

Grow a small twilight forest as a standalone SVG. Set a seed to recreate the same scene, or omit it to get a fresh one. The image uses simple vector shapes, so it stays crisp at any size and remains easy to edit.

## Use

Requires Python 3.8+; no packages to install.

```sh
python pixel_grove.py --seed 42 --output grove.svg
python pixel_grove.py --width 1200 --height 800 --trees 30 --output evening.svg
python pixel_grove.py --seed 7 > grove.svg
```

Without `--output`, SVG is written to standard output. A named output file is created only if it does not already exist. Width is 320–1600 pixels, height 240–1200, and tree density 8–48.

## License

MIT
