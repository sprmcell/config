# My i3 configs

These are just my i3 config to remove the default i3

## What do i need

Xorg dependacies, FontAwesome, i3, rofi

## Optional

i3status or polybar

## Thanks to:

[Verq](https://github.com/CordlessCoder) for helping me with the polybar monitor script

## How to use?

### First of all clone this repo
```sh
git clone https://github.com/sprmcell/i3
```
#### Then CD into it and run the following

#### for the i3 config:
```sh
rm -rf ~/.config/i3 && cp -r i3 ~/.config/
```

#### for the i3status:
```sh
sudo rm -rf /etc/i3status.conf && sudo cp i3status.conf /etc/
```

#### for polybar

```sh
sudo rm -rf /etc/polybar && cp -r polybar /etc/
```
```sh
cp pbl ~/
```
```sh
cd ~/ && chmod +x pbl
```

### If you use polybar

You're all set

### If you use i3status

uncommet the entire `bar{}` area and comment out `exec ./pbl`

## Screenshot

![i love you](https://github.com/sprmcell/i3/blob/main/screenshot.png)
