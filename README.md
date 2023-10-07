## Magic Enter plugin

### This is an intresting plugin from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/magic-enter),<BR>⚠️ please note that all credits are of oh-my-zsh team

## Usage

To use it, add `"zap-zsh/magic-enter"` to the plugins in your zshrc file:

```zsh
plug "zap-zsh/magic-enter"
```

This plugin makes your enter key magical, by binding commonly used commands to it.

To use it, add `magic-enter` to the plugins array in your zshrc file. You can set the
commands to be run in your .zshrc, before the line containing plugins. If no command
is specified in a git directory, `git status` is executed; in other directories, `ls`.

```zsh
# defaults
MAGIC_ENTER_GIT_COMMAND='git status -u .'
MAGIC_ENTER_OTHER_COMMAND='ls -lh .'

plugins=(... magic-enter)
```

**Maintainer:** [@dufferzafar](https://github.com/dufferzafar)
