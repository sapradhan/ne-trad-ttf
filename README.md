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

## installation instructions for Linux 
- install packages `ibus` and `ibus-m17n` 
- download latest distribution tar ball from releases and run this command `sudo tar xzf linux-ne-trad-ttf.tar.gz -C /usr/share/m17n`. This will :
    - copy `ne-trad-ttf.mim` to `/usr/share/m17n` (installation dir of m17n-db)
    - copy `ne-trad-ttf.png` to `/usr/share/m17n/icons`
- Restart IBus engine from from IBus applet or from terminal:
```bash
# Restart IBus
$ ibus restart
# OR if that does not work 
$ ibus-daemon -R -d
```
- new layout should be available under IBus preferences. You can access the IBus preferences by right clicking on IBus applet or from terminal:
```bash
$ ibus-setup
```
- [detailed instructions](http://nepalitankan.blogspot.com/2013/10/ne-trad-ttf-for-linux.html)

## layout image
- Original template taken from [Keyboard_layout_Zhuyin.svg](http://en.wikipedia.org/wiki/File:Keyboard_layout_Zhuyin.svg) credited to [Sakurambo](http://commons.wikimedia.org/wiki/User:Sakurambo)
- edited and png rendered using [Inkscape](http://http://inkscape.org/) 
