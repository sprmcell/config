# sexyvim
not a fork, just helps vim run and look sexy

## Installation

```sh
git clone https://github.com/sprmcell/sexyvim
```

### vim plugins

```sh
cd sexyvim && cp -r .vim ~/
```

### vimrc

`cd sexyvim` and finally `cp .vimrc ~/`

### Setting up vim

```sh
vim .vimrc
```

`then press ESC, and run the command PlugInstall, and exit vim and enter back into it`

## sudo vim doesnt show my plugins?

this is because your root user doesnt have the files

### fix?

```sh
sudo cp -r .vim .vimrc /root
```

## Discord doesnt detect vim?

Make sure you are running the latest version of discord and its NOT flatpak, sudo vim doesnt get picked up by discord
