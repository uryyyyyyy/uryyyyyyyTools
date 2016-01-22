
## Ubuntuで/boot以下がいっぱいになった場合

放っておくとどんどんlinux-imageを貯めこむらしく、複数バージョンが入ったままになっててあふれる事象が起きる。
それの解消法

```
# 現行のKernelのバージョン確認
uname -r
# stdout sample↓
# 3.19.0-47-generic


# インストール済み一覧確認
dpkg --get-selections | grep linux-image
# stdout sample↓
# linux-image-extra-3.19.0-42-generic		install
# linux-image-extra-3.19.0-43-generic		install

# 削除
sudo apt-get remove linux-image-extra-3.19.0-42-generic

```
