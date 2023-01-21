## Usage

### Installation

```shell
git clone https://github.com/catppuccin/fcitx5.git
mkdir -p ~/.local/share/fcitx5/themes/
cp -r ./fcitx5/src/* ~/.local/share/fcitx5/themes
```

### Enabling (Manually)

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` variable to:

```shell
Theme=catppuccin-mocha # or macchiato, frappe, latte
```

Later restart Fcitx5 to apply the theme.

```shell
fcitx5 -r
```

### Enabling (GUI)

1. Navigate to `Fcitx5 Configuration` application through your application launcher.
2. Select the `Addons` Tab.
3. Select the setting icon (gear-wheel) for `Classical User Interface`, located to the right.
4. Apply Catppuccin as the desired fcitx5 theme by navigating to `Theme` and later selecting Catppuccin *Flavour*.