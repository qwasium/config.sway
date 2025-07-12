# Sway/i3 config

```bash
git clone git@github.com:qwasium/config.sway.git ~/.config/sway
```

`config` is based on Fedora Sway Remix default `/etc/sway/config`.

To apply config:

```bash
swaymsg reload
```

To check `app_id`:

```bash
# first open the app window
swaymsg -t get_tree #| rg <appname>
```
