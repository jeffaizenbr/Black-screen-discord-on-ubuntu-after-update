# Black-screen-discord-on-ubuntu-after-update


```bash
vim /etc/gdm3/custom.conf
```
uncoment
```bash
#WaylandEnable=false
```

```bash
sudo systemctl restart gdm3
```

