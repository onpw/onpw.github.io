### perl: warning: Setting locale failed

```
sudo export LANGUAGE=en_US.UTF-8
sudo export LANG=en_US.UTF-8
sudo export LC_ALL=en_US.UTF-8
sudo locale-gen en_US.UTF-8
sudo dpkg-reconfigure locales
```

### Disable default ubuntu banner 

```
sudo chmod -x /etc/update-motd.d/*
touch /etc/update-motd.d/01-custom
vim /etc/update-motd.d/01-custom
#!/bin/sh
cowsay Ket noi thanh cong!

sudo chmod +x /etc/update-motd.d/01-custom
```

[back](/)