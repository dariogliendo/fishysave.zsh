## fishysave

Plugin to save and update functions and aliases directly from shell.

## Install

To install you have to add this plugin to your custom plugins folder located by default at ```$ZSH_CUSTOM```

```bash
git clone https://github.com/dariogliendo/fishysave.zsh.git "$ZSH_CUSTOM/plugins/fishysave"
```
add fishysave to the plugins array of your zshrc file:
```bash
# ~/.zshrc
plugins=(... fishysave)

```

## Usage

```bash
# Save an alias
alias lsal="ls -al"
fishysave lsal

# Save a function
function lsa() {
    ls -al
}
fishysave lsa

```
