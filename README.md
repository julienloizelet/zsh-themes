
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