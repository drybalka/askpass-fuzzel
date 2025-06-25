# askpass-fuzzel

Simple password entry menu based on [fuzzel](https://codeberg.org/dnkl/fuzzel).
Its original purpose is to be used as `ssh-askpass` tool.

## Installation

Requires `fuzzel` to be installed.
Copy the script to a directory in your PATH and make it executable, for example:

```bash
sudo cp askpass-fuzzel /usr/local/bin/
sudo chmod +x /usr/local/bin/askpass-fuzzel
```

Arch Linux users may instead build and install from the PKGBUILD:

```bash
makepkg --clean --install && rm *.pkg.tar.zst
```

## Usage

To use as SSH askpass tool, add the following to your shell configuration file (e.g., `~/.bashrc`, `~/.zshrc`, or `~/.profile`):

```bash
export SSH_ASKPASS=askpass-fuzzel
```
