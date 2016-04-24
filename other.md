- IDEの設定
- chromeへのログイン
- ファイル監視上限の設定
```
　sudo gedit /etc/sysctl.conf
　fs.inotify.max_user_watches = 24576
　sudo sysctl -p
```

- Dropbox
- GithubへのSSH鍵登録
  - ssh-keygen -t rsa -C "XXX@gmail.com"

- sudo swapoff /dev/sda5




- http://kledgeb.blogspot.jp/2013/05/ubuntu-nautilus-42.html
 
- ~/.config/gtk-3.0/bookmarks

- passwordとカギ
  - gnome pas
  - ~/.local/share/keyrings
  - login.keyring

- mouse speed
  - `xset m 1/1 1`
