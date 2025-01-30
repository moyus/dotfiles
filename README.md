<div align="center">
  <h1>🍵</h1>
</div>

## Shell
### [Homebrew](https://brew.sh/)
```bash
# install
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### [rmtrash](https://formulae.brew.sh/formula/rmtrash)
```bash
# install
brew install rmtrash
```

### [Oh My Zsh](https://ohmyz.sh/)
Oh My Zsh is a delightful, open source, community-driven framework for managing your Zsh configuration. It comes bundled with thousands of helpful functions, helpers, plugins, themes

```bash
# install
brew install zsh
chsh -s /usr/local/bin/zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### Plugins

##### [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
```bash
# install
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

```bash
# .zshrc
plugins=(zsh-syntax-highlighting)
```

##### [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
```bash
# install
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```bash
# .zshrc
plugins=(zsh-autosuggestions)
```

##### [git-open](https://github.com/paulirish/git-open)
```bash
# install
git clone https://github.com/paulirish/git-open.git $ZSH_CUSTOM/plugins/git-open
```

```bash
# .zshrc
plugins=(git-open)
```

##### [pure](https://github.com/sindresorhus/pure)
```bash
# install
git https://github.com/sindresorhus/pure.git $ZSH_CUSTOM/plugins/pure
```

```bash
# .zshrc
fpath+=$ZSH_CUSTOM/plugins/pure

autoload -U promptinit; promptinit
PURE_PROMPT_SYMBOL=➜
prompt pure
```

## Web Development

### [n](https://github.com/tj/n)
```bash
# install
brew install n
```

### [Yarn](https://classic.yarnpkg.com/lang/en)
```bash
# install
brew install yarn
```

```bash
# global packages
yarn global add tldr svgo
```

### [PHP](https://www.php.net/)
```bash
# install (see https://formulae.brew.sh/formula/php)
brew install php
```

### [Composer](https://getcomposer.org)
```bash
# install
brew install composer
```

### [Laravel](https://laravel.com/docs/7.x#installing-laravel)
```bash
# install
composer global require laravel/installer
```

### [Valet](https://laravel.com/docs/7.x/valet)
```bash
# install
composer global require laravel/valet
valet install
```

## Apps
- [Visual Studio Code](https://code.visualstudio.com)
- [iTerm2](https://www.iterm2.com)
- [滴答清单](https://dida365.com/)
