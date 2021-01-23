# Fcitx5 Gruvbox

Fcitx5 theme based on Gruvbox color.

## Screenshot

![light](./shot/light.png)

![dark](./shot/dark.png)

## Usage

### Installation

```sh
git clone https://github.com/ayamir/fcitx5-gruvbox
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-gruvbox
cp -r Gruvbox-Light/ Gruvbox-Dark ~/.local/share/fcitx5/themes/
```

### Enabling

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as

```dosini
Theme=Gruvbox-Dark
# or
Theme=Gruvbox-Light
```

Then restart fcitx5 to apply the theme.

```sh
fcitx5 -r
```
