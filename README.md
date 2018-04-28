### 日本語の解説記事は[こちら](https://qiita.com/29Takuya/items/f2b67d6296c47693b593)！


## 概要
手書き数字データ（[EMNIST](https://www.nist.gov/itl/iad/image-group/emnist-dataset)）の潜在変数を獲得する。  
### ～ポイント～ 
数字ラベルを利用することで、
1. 数字の識別に寄与する潜在変数
2. 数字の識別に無関係な潜在変数
に分離することを目指す。


## Abstract
My goal is to obtain latent variable from hand-written digit datasets(EMNIST).
### -Points-
Usinig digit labels, decompose latent variable to following two parts.
1. Latent Variable which contribute to classify digit labels.
2. Latent Variable which is irrelevant to classify digit labels. 
