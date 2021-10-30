Zenburn 256 color scheme for the color GNU ls utility.
-------------------------------------------------

Install
-------

1. Copy `dircolors` file to `~/.dir_colors`
2. Add the following three lines to your `~/.bashrc` or `~/.zshrc` file:
```
eval $( dircolors -b $HOME/.dir_colors )
alias dir='dir --color'
alias ls='ls --color'
```
To customize color
-------
1. Check color code from https://jonasjacek.github.io/colors/
2. Change the value of the variable in `~/.dir_colors` file
3. Run `source ~/.zshrc && ls`

Screenshot
----------

![screenshot](https://github.com/ivoarch/dircolors-zenburn/raw/master/img/screenshot.png)
