**Установка zsh**

```shell
sudo apt install zsh
sudo usermod -s /bin/zsh $USER
```

**Установка oh-my-zsh**

```shell
sudo apt install git
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
zsh
```

**Подсветка синтаксиса команд**

```shell
sudo apt install zsh-syntax-highlighting
or
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

**Предложение вариантов из истории**

```shell
sudo apt install zsh-autosuggestions
or
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
```

**Установка spaceship prompt**

```shell
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
```

**Установка шрифтов powerline**

```shell
sudo apt install fonts-powerline
```

**Установка шрифтов Menlo**

```shell
mkdir ~/.fonts && git clone https://github.com/abertsch/Menlo-for-Powerline.git  ~/.fonts/ && fc-cache -vf ~/.fonts
```

**Указать ZSH_THEME="spaceship" в ~/.zshrc**

```shell
source ~/.zshrc
```