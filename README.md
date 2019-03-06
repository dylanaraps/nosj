# nosj

A simple `json` parser written in pure `bash`.

The `json` is very loosely parsed and then turned into a `bash` associative array. There is no error handling of any kind in the parser and commas are ignored.

```sh
declare -A nosj
nosj["wallpaper"]='/home/black/Pictures/Wallpapers/supernicestreet.jpg'
nosj["alpha"]='100'
nosj["special.background"]='#211e1d'
nosj["special.foreground"]='#c7c6c6'
nosj["special.cursor"]='#c7c6c6'
nosj["colors.color0"]='#211e1d'
nosj["colors.color1"]='#aa9896'
nosj["colors.color2"]='#aa896e'
nosj["colors.color3"]='#a99582'
nosj["colors.color4"]='#9fa762'
nosj["colors.color5"]='#c0b8c2'
nosj["colors.color6"]='#a79ea7'
nosj["colors.color7"]='#c7c6c6'
nosj["colors.color8"]='#585655'
nosj["colors.color9"]='#aa9896'
nosj["colors.color10"]='#aa896e'
nosj["colors.color11"]='#a99582'
nosj["colors.color12"]='#9fa762'
nosj["colors.color13"]='#c0b8c2'
nosj["colors.color14"]='#a79ea7'
nosj["colors.color15"]='#c7c6c6'
```
