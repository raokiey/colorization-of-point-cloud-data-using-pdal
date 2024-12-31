# PDALを用いた3次元点群データの着色方法
[FOSS4G Advent Calendar 2024の19日目の記事](https://qiita.com/ra0kley/items/ce7d0e595651b7760cf7)の補足用のリポジトリです。  
上の記事では、PDALを用いた3次元点群データの着色方法について、解説しています。  
着色した3次元点群データのサンプルは、[こちら](https://viewer.copc.io/?copc=https://raokiey.github.io/colorization-of-point-cloud-data-using-pdal/09MD0512_colorized.copc.laz)よりCOPC Viewerで表示することができます。  
（ドラッグで移動、Ctrlを押しながらドラッグで回転できます）


## Notebook  
Google Colaboratoryにて動作確認をしています。  
- [pdal_colorizing_points_example.ipynb](./pdal_colorizing_points_example.ipynb)


## 使用したデータ  
- [神奈川県総務局デジタル戦略本部室「神奈川県 横浜北部、川崎3次元点群データ」](https://www.geospatial.jp/ckan/dataset/kanagawa-2022-pointcloud)  
    データ提供：神奈川県環境農政局緑政部森林再生課  


## ライセンスについて  
- 09MD0512_colorized.copc.laz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- ソースコード（[ノートブック](./pdal_colorizing_points_example.ipynb)）: [MIT](https://opensource.org/license/mit/)
