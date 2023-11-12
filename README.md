# linuxMint

1. to convert HEIC to JPEG etc
`sudo apt-get install libheif-examples`
2. Install Linux Mint on Mac
https://www.reallinuxuser.com/how-to-create-a-linux-mint-bootable-usb-in-macos/
3. mapping command key to control , https://askubuntu.com/questions/131900/how-do-i-switch-the-command-key-and-control-key-on-a-macbook-pro
inside:~/.Xmodmap

```
clear control
clear mod4

keycode 105 =
keycode 206 =

keycode 133 = Control_L NoSymbol Control_L
keycode 134 = Control_R NoSymbol Control_R
keycode 37 = Super_L NoSymbol Super_L

add control = Control_L
add control = Control_R
add mod4 = Super_L
```

### comands to use
1. upgrade apps
```
sudo apt update && sudo apt upgrade
```
