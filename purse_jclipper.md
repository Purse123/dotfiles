# Purse JClipper
1. Firstly, add .sh file *(recommended ~/.config)
2.
```sh
chmod +x purse_jclipper.sh
```
3. install xbindkeys and xclip packages
```sh
sudo pacman -S xbindkeys xclip
```
4. create default config for xbindkeys
```bash
xbindkeys --defaults > ~/.xbindkeysrc
```
5. inside ~/.xbindkeysrc
```sh
"bash /home/$(USER)/.config/purse_jclipper.sh"
Mod4 + period
```
6. when needed run in terminal
```sh
xbindkeys
```
**if want to stop**
```sh
killall xbindkeys
```
