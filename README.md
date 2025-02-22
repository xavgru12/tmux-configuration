# instructions

install the configuration

- using ssh(github account with ssh keys required)
```
git clone git@github.com:xavgru12/tmux-configuration.git ~/.config/tmux
```

- using hhtps
```
git clone https://github.com/xavgru12/tmux-configuration.git ~/.config/tmux
```

install tmux package manager
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

open tmux and source tmux configuration

```
tmux
```

```
cd ~/.config/tmux
```

```
tmux source tmux.conf
```

Since the configuration is sourced, the **prefix is ctrl + space**

exit tmux with:

prefix + d

enter tmux again:
```
tmux
```

have the tmux package manager install the packages with:

prefix + shift + I

leave tmux one last time with:

prefix + d

# test functionality

- enter tmux and create a shell on right side:

    prefix + %

- create a shell below:

    prefix + "

- delete current shell with:

    prefix + x and confirm with y


- switch  between the two consoles by:

    ctrl + h and ctrl + l

- enter copy mode:

    prefix + [

- use vim motions( h j k l) to navigate in copy mode

- select text with v in copy mode

- copy text with y in copy mode

- Once y is entered, it will leave copy mode and the selected text will be
saved in clipboard and can be used anywhere with ctrl c.

- text can also be copied by marking it with the cursor, not needed to ctrl c or anthing

- scroll back the terminal with mouse wheel works which basically enters copy mode

- Paste text in console with:

    ctrl + shift + v
