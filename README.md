# SentimentAnalysis
## LSTMの感情分析モデル  
ソースコード：SentimentAnalysis.py  

当時やっていたこと
RaspberryPI3で感情分析

【方法】
1. juliusで日本語の音声 to 日本語文 生成
2. Azureの翻訳APIで日本語文から英語変換（json出力）
3. 英文を本モデルに入力し推測する
