---
lab:
    title: 'ラボ 03: 非リレーショナルな Azure Data Services をプロビジョニングする'
    module: 'モジュール 03: Azure のリレーショナル データの詳細を理解する'
---

## 手順
サンプル シナリオとして、次のデータ ストアを作成することに決定しました。

* 在庫内の項目の数量に関する情報を保持するための Cosmos DB。時間経過に伴うレベルの変化を追跡できるよう、数量レベルに関する現在と過去の情報を保存する必要があります。データは毎日記録されます。
* 製造データと品質データを保持するための Data Lake Store。
* 会社が製造する製品の画像を保持するための BLOB コンテナー。
* レポートを共有するための File Storage。

このラボでは、Cosmos DB アカウントをプロビジョニングして構成し、データベース、コンテナー、サンプル ドキュメントを作成することによってテストします。また、BLOB、ファイル、Data Lake Storage を提供できる Azure ストレージ アカウントをプロビジョニングします。

1.	Microsoft Learn の演習: https://aka.ms/dp900lab03-jpn に移動し、ブラウザーで次のユニットを完了させます。 
