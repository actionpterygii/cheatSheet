# node

## nodebrew

### nodebrewアップデート
`nodebrew selfupdate`

### インストール可能なnodeバージョン確認
`nodebrew ls-remote`

### nodeインストール
`nodebrew install {{ NODE_VERSION }}`

### nodeインストール((コンパイル済)はやい)
`nodebrew install-binary {{ NODE_VERSION }}`

### インストールされているnodeバージョン確認
`nodebrew ls`

### 使うnodeバージョン指定
`nodebrew use {{ NODE_VERSION }}`

### 指定のバージョンでグローバルインストール(-g)されているのを今使っているバージョンのにも適用
`nodebrew migrate-package {{ NODE_VERSION }}`

### バージョンに別名を付ける(useで指定できるようになる)
`nodebrew alias {{ NAMAE }} {{ NODE_VERSION }}`

### バージョンの別名を削除する
`nodebrew unalias {{ NAME }}`

### nodeアンインストール
`nodebrew uninstall {{ NODE_VERSION }}`