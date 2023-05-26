# Rofi recording script
Record your screen, desktop audio and microphone input at the same time

## Changing microphone
If the default microphone source doesn't work for you, then execute the following command:
```
pactl list sources short
```
Find your microphone there and change `$micsource` variable in the `recordrofi` script.

## Installation
```
$ git clone https://github.com/Andrey0189/recordrofi
$ cd recordrofi
$ chmod +x ./install-theme.sh recordrofi
$ ./install-theme.sh
$ sudo mv recordrofi /usr/bin
```
Have fun!
```
$ recordrofi
```
