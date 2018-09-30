# Doma - シンプルで強力なDBアクセスフレームワーク - の話

## セッション概要

Doma( http://doma.readthedocs.org/ )はJava 8対応のDBアクセスフレームワークで次のような特徴があります。

・Pluggable Annotation Processing APIを用いてコンパイル時にコードの生成や検証を行う
・DB上のカラムの値を自由にJavaオブジェクトにマッピングできる
・2-way SQLと呼ばれるSQLテンプレートファイルを使用した検索
・LocalDate、Stream、Optionalなどへの対応

これらの特徴を詳しく解説し、Domaがどういうフレームワークなのかを知って頂きます。

また私がDomaを実践してきた中で得た知見、例えばCDIなどのDIコンテナとの併用の仕方や、コーディングミスをコンパイル時エラーとして検出するための工夫などをご紹介します。

## 対象者

DBアクセスフレームワークの選択の幅を広げたい人。またはDomaを使っており、公式ドキュメントには記載されていない実践から得た知見を知りたい人

## イベント

http://www.java-users.jp/?page_id=2056

## 結果

落選
