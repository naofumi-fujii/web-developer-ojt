# 課題1内容

[ojt-linux-vagrant](https://github.com/keitakn/ojt-linux-vagrant) を使い以下の環境を構築して頂きます。

作成するのはNode.jsの実行環境 + OSの基本設定です。

完了条件として以下の条件を満たして頂きたいです。

- OSの各パッケージが最新に更新されている事（yumアップデート）
- nodebrewによりバージョン管理が行われており最新のNode.jsがインストールされている事（Node.jsは特別なパッケージ等は入れなくてOKです）
- タイムゾーンが日本時間（JST) になっている事
- localeが日本語設定になっている事
- swap領域が追加されている事（どのくらいの領域を確保するかはお任せします）
- 個人名のユーザーが追加されている事（追加したユーザーでサーバ上にSSH接続が出来る事）
- IPv6が無効化されている事

## アウトプット

成果物として、環境構築の手順を示したQiitaの記事を作成して下さい。

※ インターネット上に公開されてしまうので抵抗がある場合は限定共有投稿でも構いません。

あまり良い書き方でもないですが参考までに私が過去に書いた記事 [Rails5,MySQLの開発環境構築を行う](https://qiita.com/keitakn/items/b19bf134ff76e6e579eb) を共有させて頂きます。

記事は下記の点に注意して作成して下さい。

- 書いてある手順通りに行うと間違いなく環境構築が出来る事
- 各コマンドを実行している理由（なぜそれが必要かを）が記載されている事

## 分からない時

自分で調べてどうしても分からない時はメンターに相談しましょう。

メンターは質問されたら丁寧に対応する事！

[質問は恥ではないし役に立つ](https://qiita.com/seki_uk/items/4001423b3cd3db0dada7) という素晴らしい記事がありましたので、参考にすると良いでしょう。

## 参考になりそうなリンク

- [Amazon EC2 初期設定 | AmazonLinuxを立ち上げたら最初にすべき10の設定 [sshログイン〜ec2-userの削除まで]
](http://www.carameltrip.com/entry/20170112/1484222151)
- [Amazon Linux サーバセットアップメモ](https://qiita.com/Ping/items/09deb80a0be86d5e3145)

