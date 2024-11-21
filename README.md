# Tokyo Night Theme for Atuin

![screenshot of atuin with tokyo night theme](atuin.png)

## Install

```bash
# make the themes directory if it doesn't exist
mkdir -p ~/.config/atuin/themes

# clone repo to wherever you store your code
git clone https://github.com/esoterick/atuin-tokyo-night
cd atuin-tokyo-night
ln -s tokyo-night.toml ~/.config/atuin/themes/tokyo-night.toml
```

## Enable

Edit your atuin configuration at `~/.config/atuin/config.toml`

```toml
[theme]
name = "tokyo-night"
```
