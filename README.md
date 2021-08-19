# Alacritty termcolor

Sets the color and opacity of your alacritty terminal with the command
`termcolor` by modifying your alacritty config file.

## Prerequisites

You must have python3 installed. Either use the provided alacritty.yml file or
add the following to your own:

```yaml
import:
  - ~/.config/alacritty/schemes.yml
```

Additionally, remove or comment out any references to the terminal color.

If you're using the config in this repository, make sure the settings are how
you want them to be. You may not have everything I do.

## Usage

Clone this repository and copy the files to your alacritty config folder (by
default this location is `~/.config/alacritty/`)

Install the `termcolor` executable to your PATH:

```bash
install ~/.config/alacritty/termcolor ~/.local/bin/termcolor
```

Optionally, for bash completion, source the `termcolor.bash-completion` file
into your `.bashrc` file:

```bash
echo '. "$HOME/.config/alacritty/termcolor.bash-completion"' | tee -a .bashrc
```
