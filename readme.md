### First time setup ssh:

```
scp -r root@tim-server:/mnt/user/Tim-Server/Backups/Linux/rsync/.ssh /home/tim/
chmod +x /home/tim/.ssh/setup.sh
./home/tim/.ssh/setup.ssh
```

### Local Run:

```
sudo ansible-pull -U https://github.com/TimLisemer/Ansible-Desktop.git
sudo reboot
```

### Todo:

Add yay

Add npm --> npm install -g neovim sass
