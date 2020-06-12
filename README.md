# Config Files with MR

Can be setup with
```bash
vcsh clone git@github.com:StopMotionCuber/mr-config.git mr
mr update
```

Make sure that all dependencies for Python are available.
Furthermore the `mr update` may fail for tmux. This can be prevented by being run in tmux

## Install Dependencies

### Ubuntu/Debian/Raspbian
```bash
sudo apt install build-essential libbz2-dev libsqlite3-dev libreadline-dev libssl-dev libffi-dev
```

## zsh-plugins
```bash
sudo apt install zsh-autosuggestions zsh-syntax-highlighting
```

## Change Shell to zsh
```bash
chsh -s /bin/zsh $USER
```
