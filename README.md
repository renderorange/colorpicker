# colorpicker

A small tool for X11 that writes the color value on your screen at the cursor position to stdout, in RGB and Hex.

## SYNOPSIS

```
colorpicker [options]
  -o, --one-shot:  one shot
  -h, --help:      display this dialogue
```

## USAGE

Left click to print the pixel color in RGB and Hex.  Prints again for each click.  Any other mouse click exits.

```
$ ./colorpicker
R: 247, G: 247, B: 247 | Hex: #F7F7F7
R: 255, G: 255, B: 255 | Hex: #FFFFFF
R: 242, G: 242, B: 242 | Hex: #F2F2F2
```

The `--one-shot|-o` option prints only a single value then exits.

```
$ ./colorpicker -o
R: 255, G: 255, B: 255 | Hex: #FFFFFF
```

## INSTALLATION

```
$ make
$ make install
$ make clean
```

Run `make uninstall` to uninstall.

## DEPENDENCIES

`XLib`

## LICENSE

MIT
