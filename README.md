# jupyter-notebook

## 確率ロボティクス　課題　21S1011清岡優祐

### 参考
書籍「つくりながら学ぶ！深層強化学習」、著者：株式会社電通国際情報サービス 小川雄太郎、出版社: マイナビ出版 (2018/6/28).  
書籍「詳解 確率ロボティクス Pythonによる基礎アルゴリズムの実装」，著者：上田隆一 (KS理工学専門書) (日本語) 単行本（ソフトカバー） (2019/10/27)

### 取り組んだ内容
10x10の簡単なマップを用意し，Q学習を用いて最適な方策の獲得を目指す．
1ステップごとの学習の様子を可視化した．

### Q学習
ロボットが行動した後に得られる情報を用いて，行動価値関数を更新していくアルゴリズムである．  
更新は以下の式で行う．
![image](https://user-images.githubusercontent.com/50820768/148540239-e87c6a4e-9e24-4a28-941e-d6b6cbcbfd89.png)

### 環境の設定
10x10のタイルとした．
左下をスタートとし，右上をゴールとした．  
<img width="271" alt="image" src="https://user-images.githubusercontent.com/50820768/148540862-03ace60e-779b-4c31-99f6-5f1d75bbe113.png">

### 結果
#### 1step
<img width="237" alt="image" src="https://user-images.githubusercontent.com/50820768/148542775-b8a51131-ea80-430d-9d3d-02c7f90a7c07.png">

  
#### 50step
<img width="237" alt="image" src="https://user-images.githubusercontent.com/50820768/148542893-102802b3-d8e1-402b-9983-6ffc053b8d87.png">

  
#### 100step
<img width="237" alt="image" src="https://user-images.githubusercontent.com/50820768/148542662-021be462-c9d6-4b18-97df-88b1ecd04501.png">

### まとめ
Q学習を用いて，10x10の簡単なマップでゴールまで行く方策が獲得できた．  
ステップごとの可視化をした結果50step付近で収束していることがわかった．






