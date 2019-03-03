# nosj

A simple `json` parser written in pure `bash`.

The `json` is very loosely parsed and then turned into a `bash` associative array. There is no error handling of any kind in the parser and commas are ignored.

```sh
➜ nosj ~/.cache/wal/colors.json
nosj[special.foreground]
nosj[alpha]
nosj[special.background]
nosj[wallpaper]
nosj[special.cursor]
nosj[colors.color10]
nosj[colors.color11]
nosj[colors.color12]
nosj[colors.color13]
nosj[colors.color14]
nosj[colors.color15]
nosj[colors.color9]
nosj[colors.color8]
nosj[colors.color1]
nosj[colors.color0]
nosj[colors.color3]
nosj[colors.color2]
nosj[colors.color5]
nosj[colors.color4]
nosj[colors.color7]
nosj[colors.color6]
```

## Usage

```sh
# Source the json data.
. nosj file.json
```
