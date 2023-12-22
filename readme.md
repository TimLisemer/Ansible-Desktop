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

Add npm --> npm install -g neovim
```
systemctl --user daemon-reload
systemctl --user enable --now home_sync.timer --now
```



git init
git remote add origin root@tim-server:/mnt/user/Tim-Server/Backups/Linux/git
git branch -u origin/main
git pull origin main
# Resolve any conflicts if needed
git add .
git commit -m "Merge changes from origin/main"
git push origin main
