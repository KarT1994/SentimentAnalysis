# project_privious2020
### 2020年以前の成果物のまとめ
## 【目的】
ローカルに保管されていた趣味で作ったプロジェクトを整理。
AIエンジニアにスキルアップするため、ポートフォリオとして活用。
好きなように参考にしてください。


## 【成果物】
### 1. raspberryPiを用いた音声認識による感情判別

 以下の①②の方法でraspbberyPI上で音声→文章→ネガティブポジティブ判定をする。  
 ① juliusを利用したエッジでの音声→日本語文章変換　＋　Azure Speech Translationを利用した日本語→英語変換。  
  英語に変換するのは、②の文章→感情判定の学習用データに日本語で利用できそうなものが見つからず、英語版ツイッターコーパスを利用したため。  
  (よく探してみたら日本語音声から英語文章を生成できるSaasが存在するらしく、こっちの方が便利な気がする)。  
 ②LSTMによる文章→感情判定結果変換  
  機械学習にLSTMを用いたニューラルネットワークを構築。
