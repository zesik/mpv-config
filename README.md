# mpv Configurations

My configurations for [mpv].

## Installation of mpv on OS X

Install mpv using [Homebrew].

```bash
brew install mpv --with-bundle
brew linkapps mpv
```

## Applying Configurations

mpv loads configurations files at `~/.config/mpv`.
Clone this repository into that directory.

```bash
mkdir -p ~/.config
git clone git@github.com:zesik/mpv-config.git ~/.config/mpv
```

[mpv]: http://mpv.io
[Homebrew]: http://brew.sh/

