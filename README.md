# 概要

これは [Generamba](https://github.com/rambler-digital-solutions/Generamba) のためのテンプレートカタログになります。

# 特徴

このテンプレートは「View」、「Presenter」「Interactor」「Router」の４つで構成された、VIPER テンプレートになります。

## E がない

このテンプレートには E(Entity)をテンプレートに含めていません。何故なら Entity は各モジュール内毎に参照が収まるものだとは考えていないためです。

## input / output がない

適度に柔軟性を持たせるために要素毎に input / output の分離は行わないようにしています。

## フロー

VIPER としてのフローを保つために、ViewController の遷移を Router.createModule()を起点とし、各要素からフローに関連している要素にアクセスできるような作りとしています。

## Indentation "2"

インデントはスペース 2 つで作成しています。
