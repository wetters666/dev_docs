# 3Dモデルの内容の確認 - Cute Series (MESHTINT)

- [目次へ](./../index.md)

## 作成済みプレハブの確認

![model_structure_sample01](./media/model_structure_sample01.png)

プレハブを確認すると、上のようになっている。これは一般的な（？）3Dモデルの構造と異なる。

一般的な人型3Dモデルの構造は、

![model_structure_suriyun](./media/model_structure_suriyun.png)

このように、ボーン（リグ）系のルート（ここでは「Root_M」）とメッシュ系のルート（ここでは「Mesh」）がある。

![model_structure_samples](./media/model_structure_samples.png)

しかし、Cute Seriesのモデルの場合、メッシュは、ルート（ここでは「Female Outfit Fan 10」または「Female Outfit Fan 02」）に1つだけあり、更にリグ系のツリーの中にも「Female Head 01 Fair」などのメッシュがある。

後ほど試すが、Cute Seriesでは、「素体」と「パーツ」があってそれぞれを複数種類から選べるようになっている。ルートに1つあるメッシュが「素体」、リグ系のツリーの中に点在するメッシュが「パーツ」に相当する。

- [目次へ](./../index.md)

