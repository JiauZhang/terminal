### 安装 Fish Shell
```shell
sudo apt-add-repository ppa:fish-shell/release-3
sudo apt-get update
sudo apt-get install fish
```
修改默认 shell 为 Fish Shell
```shell
# 查看当前 shell
echo $SHELL
# 修改默认 shell
chsh -s /usr/bin/fish
```

### 安装 Oh My Zsh
```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### 配色方案
- Afterglow
- Andromeda
- Arthur
- Builtin Solarized Dark
- Chalk
- Chalkboard
- Ciapre
- Duotone Dark
- Elemental
- Espresso
- Espresso Libre
- Fideloper
- Firewatch
- Flatland
- Hybrid
- Later This Evening
- LiquidCarbon
- N0tch2k
- Neutron
- OceanicMaterial
- Rebecca
- Relaxed
- Snazzy
- SoftServer

### 颜色映射
```json
// user_name@pc_name current_path>
"black"
"red"
"green" for directory box and current_path
"yellow"
"blue" for directory
"purple"
"cyan"
"white"
"brightBlack"
"brightRed"
"brightGreen" for user_name
"brightYellow"
"brightBlue"
"brightPurple"
"brightCyan"
"brightWhite"
"background"
"foreground"
```