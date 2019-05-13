![screenshot](https://github.com/nathanleighsays/leftwmthemes/blob/master/themes/marooned/marooned1.jpg)

MAROONED  
a leftwm theme by Nathan Leigh  
www.nathanleigh.net

# Requirements:

polybar  
https://github.com/polybar/polybar  
compton  
https://github.com/chjj/compton  
mpc  
https://github.com/MusicPlayerDaemon/mpc  
mpd  
https://github.com/MusicPlayerDaemon/MPD  

# Fonts

font awesome  
https://fontawesome.com/  
string literal  
https://fonts2u.com/string-literal-437-medium.font  

# ./extras/

GTK Marooned Theme  
Numix Marooned Icons  
QT Marooned Color Scheme  
String Literal 439 (Modified String Literal 437 for use with Marooned)  

# Installation:

mkdir ~/.config/leftwm/themes/marooned  
cp -R ./marooned ~/.config/leftwm/themes/marooned  
ln -s ~/.config/leftwm/themes/marooned ~/.config/leftwm/themes/current  
mv ~/.Xresources ~/.Xresources.old  
pkill leftwm-worker  
