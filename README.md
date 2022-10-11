
# Zsh theme for Oh My Zsh

## Initial version

- Install the firebase plugin : https://github.com/Seqi/firebase-zsh

- Clone this repo in `/some/path/to/clone`

- Add a symbolic link th the file jlo.zsh-theme in your `~/.oh-my-zsh/custom/themes`

   - `ln -s /some/path/to/clone/jlo.zsh-theme ~/.oh-my-zsh/custom/themes/jlo.zsh-theme`
   
- In your `~/.zshrc` file , set your theme to jlo   : `ZSH_THEME="jlo"`

- relaunch zsh or open a new terminal


## p10k version

- Install the [powerlevel10k theme](https://github.com/romkatv/powerlevel10k) and follow instruction to enable it as 
  zsh theme.

- Replace the `~/.p10k.zsh` file by the provided `jlo-p10k.zsh` file

- Restart `zsh` with `exec zsh`

### Phpstorm issue

As it seems that PHPSTORM has some issue with emoji rendering, we can use, as a workaround, the following snippet in 
the `~/.zshrc` file: 

```bash
if [[ $__INTELLIJ_COMMAND_HISTFILE__ ]]; then
  ZSH_THEME="jlo"
else
  ZSH_THEME="powerlevel10k/powerlevel10k"
fi
```

@See https://github.com/romkatv/powerlevel10k/issues/1128#issuecomment-734655404 
@See https://youtrack.jetbrains.com/issue/IDEA-248010
