ne-trad-ttf
===========

nepali traditional layouts mostly compatible with preeti, kantipur like ttf fonts. detailed description [here](http://nepalitankan.blogspot.com/2013/10/nepali-traditional.html)

## installation instructions for Windows 
- download `ne-ttf.zip` from windows/bin directory 
- extract and run setup.exe
- Go to control panel->Regional settings->Keyboards and languages
- new keyboard layout should be available under Nepali language named Nepali Traditional TTF
- src for [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339) in `klc` folder
- [detailed instructions](http://nepalitankan.blogspot.com/2013/10/ne-trad-ttf-for-ms-windows.html)

## installation instructions for Ubuntu 
- install packages `ibus` and `ibus-m17n` 
- copy `ne-trad-ttf.mim` to `/usr/share/m17n` (installation dir of m17n-db as of 12.04)
- copy `ne-trad-ttf.png` to `/usr/share/m17n/icons`
- may need to restart ibus engine
```bash
# Restart Ibus
$ sudo ibus restart
```
- If above command failed you might need to restart `ibus-daemon`
```bash
$ sudo ibus-daemon
```
- new layout should be available under iBus preferences, starting with Ubuntu13.10 `ibus preferences` is not available in Settings and we have to start it from terminal.

### Open IBus Preferences from terminal

```bash
$ sudo ibus-setup
```
- [detailed instructions](http://nepalitankan.blogspot.com/2013/10/ne-trad-ttf-for-linux.html)

## layout image
- Original template taken from [Keyboard_layout_Zhuyin.svg](http://en.wikipedia.org/wiki/File:Keyboard_layout_Zhuyin.svg) credited to [Sakurambo](http://commons.wikimedia.org/wiki/User:Sakurambo)
- edited and png rendered using [Inkscape](http://http://inkscape.org/) 
