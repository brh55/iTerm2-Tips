# dev-tricks [![cat dancing](http://orig06.deviantart.net/3978/f/2009/295/a/4/dancin_cat_by_xxxruno_murochoxxx.gif)](http://xxxruno-murochoxxx.deviantart.com/gallery/)
A set of frequently used tips and tricks to accelerate your workflow. Feel free to contribute and submit PRs for any helpful tips.

## Terminal
### Aliases
Aliases can help make those tedious task just a bit easier. They are increasingly important for very commonly used set of commands. Below are examples of many commonly used aliases, feel free to name your aliases as you please.

To set aliases by adding to your rc files like such: `alias gs='git status`

#### Git Aliases
    alias gs='git status '
    alias ga='git add '
    alias gb='git branch '
    alias gc='git commit'
    alias gp='git pull'
    alias gps='git push'
    alias gpsu='git push --set-upstream origin'
    alias gd='git diff'
    alias got='git '
    alias get='git '

#### Python Aliases
    alias activate='source venv/bin/activate'
    alias pyenv='virtualenv venv'
    alias pydeps='pip install -r requirements.txt'
    alias pyinstall='pip install '

### Miscellaneous
#### Reverse-I-Search
Search back through your history list of commands matching with your entered character.

    ctrl + R
![reverse-i-search](http://g.recordit.co/Et4oAhjoYl.gif)

#### The Fuck
[The Fuck](https://github.com/nvbn/thefuck) is a "magnificant app" that saves you from the troubles of mistypes. All with a simple command:

    $ fuck
![fck example](http://g.recordit.co/m1Ebdn4jOn.gif)

Want to keep it work appropriate? Set an alias: `alias fml='fuck'`

## iTerm2
[iTerm2](https://www.iterm2.com/) is everything and more you want in a terminal, and is a highly recommended for anyone still using terminal.

### Pane Splitting
Vertical Split: `cmd + D`

Horizontal Split `cmd + shift + D`
![Pane Split Example](http://g.recordit.co/IkDEU68TPK.gif)

### Moving an external pane into another pane
![Demo Panel Move In](http://g.recordit.co/K1RGqlpGZX.gif)

## Sublime
### Quick Add Next
Rapidly find occurences of a matching set of characters:

    cmd + D

![quick add demo](http://g.recordit.co/y4ElMIkG3R.gif)

## `oh-my-zsh`

Community-driven framework for managing zsh configurations:

[https://github.com/robbyrussell/oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

Themes can be found [here](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)

### Why do I need it?

`oh-my-zsh` not only provides amazing themes for your shell, but it also offers custom aliases for *nix commands, custom plugins for softwares such as git, cURL, and much more. A complete list of plugins can be found [here](https://github.com/robbyrussell/oh-my-zsh/tree/master/plugins).

Speaking from personal experience, `oh-my-zsh` has helped me **tremendously**.
