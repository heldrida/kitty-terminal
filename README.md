# Kitty terminal dot files

Kitty is a fast, feature-rich, GPU based terminal emulator

## Fonts

Find a suitable font at:


[Nerd fonts](https://www.nerdfonts.com/)

[Nerd fonts repo](https://github.com/ryanoasis/nerd-fonts#option-3-install-script)

[Homebrew cask fonts](https://github.com/Homebrew/homebrew-cask-fonts/tree/master/Casks)

Find how they look like:

https://www.programmingfonts.org/#firacode

For example, installed via homebrew cask fonts:

Add tap

```sh
brew tap homebrew/cask-fonts
```

Install

Kitty-themes submodule

```sh
git submodule update --init --recursive
```

```sh
brew install font-fira-code-nerd-font
```

Find the kitty compatible fonts by:

```sh
kitty +list-fonts
```

# Themes

```sh
kitty +kitten themes
```

[Preview themes](https://github.com/dexpota/kitty-themes)

## Reference:
https://sw.kovidgoyal.net/kitty

https://github.com/dexpota/kitty-themes
