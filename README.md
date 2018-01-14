# atom-setting
atomの設定

## パッケージ
### リポジトリに反映させる場合
下記apmコマンドを実行。  
`apm list --installed --bare > packages.txt`  
出力されるpackages.txtを「C:\\Users\\ユーザ名\\.atom」に配置し、push。

### インストールする場合
下記apmコマンドを実行。  
`apm install --packages-file packages.txt`  
実行後packages.txtに記載されているパッケージがインストールされる。
