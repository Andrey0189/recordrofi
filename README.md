# Rofi recording script
Record your screen, desktop audio and microphone input at the same time

## Changing microphone
By default this script uses my microphone name, which is probably not suitable for you. To change it execute the following command:
```
pactl list sources short
```
Find your microphone there and change `$micsource` variable in the `recordrofi` script\n
Also you can just change the `$micsource` value to `"default"`, but this may not work in some cases

## Instalation
```
git clone https://github.com/Andrey0189/recordrofi
chmod +x ./install-theme.sh recordrofi
./install-theme.sh
sudo mv recordrofi /usr/bin
```
Have fun!
```
recordrofi
```
