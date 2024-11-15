**A collection of miscellaneous config files used in various places.**

`starship.toml` is the configuration file for the starship shell prompt. Starship needs to be enabled in `.bashrc` with:
```
eval "$(starship init bash)"
```
By default, `starship.toml` needs to be placed in `$HOME/.config/`, but the path can be redefined in something like `.bashrc` with: 

```
export STARSHIP_CONFIG=~/example/non/default/path/starship.toml
```
This specific configuration file also need a "Nerd Font", such as FiraCode, which can be installed with:
```
sudo apt install fonts-firacode
```
