# powerlevel9k-dark-theme
A powerlevel9k based theme for the dark theme of the gnome terminal.

# Requirements
- `zsh` shell
- `oh-my-zsh`
- `powerlevel9k` theme

# Theme
Add the following lines to your `.zshrc` file:

```sh
POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(ssh dir vcs dir_writable)
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=(root_indicator time status)
POWERLEVEL9K_RIGHT_SEGMENT_SEPARATOR=''
POWERLEVEL9K_MULTILINE_FIRST_PROMPT_PREFIX=''
POWERLEVEL9K_MULTILINE_LAST_PROMPT_PREFIX='›'
POWERLEVEL9K_PROMPT_ON_NEWLINE=true

POWERLEVEL9K_DIR_BACKGROUND=237
POWERLEVEL9K_DIR_DEFAULT_BACKGROUND=075
POWERLEVEL9K_DIR_HOME_BACKGROUND=075
POWERLEVEL9K_DIR_HOME_SUBFOLDER_BACKGROUND=075
POWERLEVEL9K_DIR_PATH_SEPARATOR="%F{008}/%F{000}"

POWERLEVEL9K_VCS_CLEAN_BACKGROUND=077
POWERLEVEL9K_VCS_UNTRACKED_BACKGROUND=227
POWERLEVEL9K_VCS_MODIFIED_BACKGROUND=227

POWERLEVEL9K_TIME_FOREGROUND=ligtgray
POWERLEVEL9K_TIME_BACKGROUND=clear

POWERLEVEL9K_STATUS_BACKGROUND=clear
POWERLEVEL9K_STATUS_OK_BACKGROUND=ligtgray
POWERLEVEL9K_STATUS_ERROR_BACKGROUND=clear
```
