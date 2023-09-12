# User-Lorem-Ipsums
phpを用いてダイナミックwebサーバーをAWS上に構築
## アプリケーション概要
Fakerを用いて生成したUserデータをHTMLで出力し, Webサイトを表示. <br>また、Markdown, JSONやTextファイルなどで選択してファイル形式でランダムユーザーデータを出力可能.
## 技術
- PHP
- AWS EC2
- NGINX
- PHP-FPM<br>
<br>
PHPを用いてアプリケーションを実装. <br> EC2インスタンス上にNGINXをリバースプロキシとして用いて、PHP-FPMのFastCGIサーバに送信し、リクエストを処理する.<br>
<img width="729" alt="スクリーンショット 2023-09-12 12 05 15" src="https://github.com/KoshinHagimoto/User-Lorem-Ipsums/assets/127278864/4c61ecdd-8fdb-47b7-975a-a9eea032aa73">
