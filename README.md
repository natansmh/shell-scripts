# Shell Scripts Collection

Collection of useful scripts I made to get things done from the terminal.

# Usage Instructions

1. Clone the repo:
```bash
git clone https://github.com/natansmh/shell-scripts.git ~/.local/bin/
```

2. Give execution permission to the scripts: ```chmod +x ~/.local/bin/shell-scripts/*.sh```

3. Additionally, you can add an alias to your shell config or add the directory to PATH:

```
export PATH="$HOME/.local/bin/shell-scripts:$PATH"
# or
alias script-name="~/.local/bin/shell-scripts/script-name.sh"
```

4. Execute any script directly with:

```
~/.local/bin/shell-scripts/script-name
# or (if on PATH/Alias)
script-name
```

# Available Scripts

* flathub-install - TUI to fuzzy find and install flatpaks from Flathub with info.

  Required packages: ```flatpak``` ```fzf``` ```awk``` ```tput```
