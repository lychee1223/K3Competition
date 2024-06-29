[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lychee1223/K3Competition/blob/main/k3-competition.ipynb)
[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/lychee1223/k3-competition-2024)

# K3 Competition 2024
本リポジトリは法政大学計算技術研究会で私が主催したKaggleコンペ [K3 Competition 2024](https://www.kaggle.com/t/bedf75123af7434daf6b5b3f5db969f0) で用いたベンチマークです．<br>

## 手法
以下の事前学習済みモデルをファインチューニングし，アンサンブルしたものを提出しました．
- [ResNet](https://arxiv.org/abs/1512.03385v1)
- [EfficientNetV2](https://arxiv.org/abs/2104.00298v3)
- [ViT](https://arxiv.org/abs/2010.11929)

また，Online Augmentationとして，学習時には画像に以下の処理を施しました．
- [RandAugment](https://arxiv.org/abs/1909.13719)
- [AugMix](https://arxiv.org/abs/1912.02781)

## 結果
![image](https://github.com/lychee1223/K3Competition2024/assets/110546438/3bf026b0-00b0-44a9-9983-9d47d61f2d49)

