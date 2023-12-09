### First time setup ssh:

```
scp -r root@tim-server:/mnt/user/Tim-Server/Backups/Linux/rsync/.ssh /home/tim/
chmod +x /home/tim/.ssh/setup.sh
./home/tim/.ssh/setup.ssh
```

### Local Run:

```
sudo ansible-pull -U https://github.com/TimLisemer/Ansible-Desktop.git
curl -sSL https://raw.githubusercontent.com/TimLisemer/Ansible-Desktop/main/files/dconf.txt | dconf load /
```

### Manually RSync

```
rsync -aP --exclude-from=/home/tim/.rsync-exclude.txt /home/tim/ root@tim-server:/mnt/user0/Tim-Server/Backups/Linux/rsync/
```

### Todo:

Add yay
Add npm --> npm install -g neovim
