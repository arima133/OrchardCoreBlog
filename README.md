# OrchardCoreBlog

Japanese only.
I'm japanese native speaker.

# これはなに?
Orchard Core を使うためのテンプレート

# 特徴 Features
Orchard Core が簡単に使える

# 必要なもの Requirement
* .net 5
* OrchardCore.Application.Cms.Target v1.01

# インストール Installation
インストールなぞ不要
 
# 使い方 Usage

## ビルドする
* git でクローンする
* クローン下ソリューションをビルドする
* できた!

## Azure で使ってみる
* まず Azure を使えるようにしておく
* Azure で Web App Service リソースを追加する 名前は任意
* .net 5 を使うように設定する
* リソースが完成したら、作ったリソースに移動
* おそらく、概要ページに移動する
* 稼働していると面倒なので、停止する 停止リンクは概要のページにある
* 停止した通知を待つ
* Web App Service リソースのメニューから デプロイ センター を選択
* ソースに外部 Git を選択
* リポジトリに https://github.com/arima133/OrchardCoreBlog.git
* ブランチに master
* リポジトリの種類はパブリック
* 保存をクリック しばらく放置
* サイトを開くと初期設定画面が表示される
* 設定方法はここ https://docs.orchardcore.net/en/latest/docs/getting-started/
* Azure で Sqlite は使えない様子。オンプレミスに変更するなり、課金して Azure SQL Server を作るなりする。

## なんか動かなくなったよってとき
設定した情報は
"home\site\wwwroot\App_Data\Sites\Default" に保存されている。
この Default ディレクトリーを消せば初期設定画面に戻れる。

# 注意点 Note
指定するリポジトリはフォークなりして複製すると安心。
みんな大好き自己責任。ライセンスを見てね。

# 作った人 Author
* 作成者 : arima133
* 所属 : 
* E-mail : 
 
# ライセンス License
2021-10-29 18:00 JST 現在
NYSL Version 0.9982
http://www.kmonos.net/nysl/
