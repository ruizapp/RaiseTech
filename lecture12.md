# 第12回課題

## CircleCi動作手順

プロジェクトのリポジトリ（RaiseTech)に、".circleci/config.yml"ファイルを作成する

![](image/cfn-lint.png)

上記のようなエラーが出たので、cloudformationフォルダを作り、その中にymlファイルを移動した。

再実行すると

![](image/cfn-lint2.png)

RDSのパスワードがハードコードだったためエラー

ハードコードを直して再実行すると...

![](image/cfn-lint3.png)

成功しました。



