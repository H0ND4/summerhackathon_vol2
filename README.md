# summerhackathon_vol2
2020/09/09から2020/09/16に行われたハッカソンの成果物です

## URL
### 管理者: 石原 (CloudRun)
https://sh2-tlnesjcoqq-an.a.run.app

## ディレクトリ構成

summerhackathon_vol2/  
┣www/ (アプリ本体)  
┃┣html/ (公開ファイル置き場)  
┃┃┣static/(静的ファイル置き場)  
┃┃┃┗img/(アプリで使う画像置き場)  
┃┃┣favicon.ico (ファビコン)  
┃┃┗robots.txt (googleクローラー等への指示)  
┃┣templates/ (Flaskアプリで使うHTMLテンプレート置き場)  
┃┣Dockerfile (環境構築方法の記述,CaaSへのデプロイ用)  
┃┣wsgi.py (Flask鯖本体/ルーティング等の処理実装箇所)  
┃┣main.py (アプリの機能実装箇所)  
┃┗requirements.txt (必要なライブラリ一覧)  
┣assets (README.mdで使う画像置き場)  
┣.gitignore (git pushでpushしたくないファイル一覧)  
┣cloudbuild.yaml (CaaSへのデプロイ指示書)  
┣LICENSE (MIT: ご自由にお使いください)  
┗README.md この文書  


## ローカルでの使い方
`git clone https://github.com/jSm449g4d/summerhackathon_vol2`  
`cd summerhackathon_vol2/www`  
`pip install -r requirements.txt`  
`python wsgi.py`  
詳しくは全部**Dockerfile**に書いてある(笑)

## 開発の進め方
1. なんか思いついたことや**雑談**とかあったらissueを立てる(上のCode,Issues,...,の所)  
2. 暇なときにissue見て議論する  
3. 解決できそうならプルリク送ったりマージしたりします  


テスト　西尾
テスト　辻田
