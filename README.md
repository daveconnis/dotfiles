# Setup

## Use Homebrew

```
brew install wget
wget --no-check-certificate https://github.com/daveconnis/dotfiles/raw/master/tools/install.sh -O - | sh
```

This install script might not work. Also, we're using Oh-my-zsh which changes the file structure, so do this instead.

1. Create a `.zshrc` file that contains the ZSH files here, aka all the aliases, prompts, editor, etc.

2. Bin files can go into the .oh-my-zsh git folder as new files.

3. In '.zshrc`, be sure to link the RPROMPT path to where the `git-cwd-info` lives and also give the appropriate access permissions by running `sudo chmod 755 'filename'`
