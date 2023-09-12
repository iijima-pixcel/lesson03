# 第三回課題
1. サンプルアプリケーションのデプロイ  
![ブラウザでの接続確認](https://github.com/iijima-pixcel/image/blob/main/%E3%82%B5%E3%83%B3%E3%83%97%E3%83%AB%E3%82%A2%E3%83%97%E3%83%AA%E3%82%B1%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E8%B5%B7%E5%8B%95.png)

2. APサーバの名前とバージョン  
   2-1  
   名前puma  
   バージョン5.6.5  
![puma.ver](https://github.com/iijima-pixcel/image/blob/main/puma%20ver.png)       　　  
   2-2  
   APサーバ終了時の挙動  
   以下の画像が表示されブラウザ接続が不可能になる。  
![APサーバー終了](https://github.com/iijima-pixcel/image/blob/main/ap%E3%82%B5%E3%83%BC%E3%83%90%E3%82%B9%E3%83%88%E3%83%83%E3%83%97.png)  

3. DBサーバの名前とバージョン  
   3-1  
   名前MySQL  
   バージョン8.0.34  
   3-2
   DBサーバ終了時の挙動  
   以下の画像が表示されブラウザ接続が不可能になる。  
![DBサーバー終了](https://github.com/iijima-pixcel/image/blob/main/db%E3%82%B5%E3%83%BC%E3%83%90%E3%82%B9%E3%83%88%E3%83%83%E3%83%97.png)  

4. Railsの構成管理ツールの名前は？  
   bundler  

#今回の課題で学んだこと  
1. AWSでのVPC作成したのち、cloud9が起動できなかった。パブリックipが割り当てられてなかったためである。パブリックipを自動割り当てにする。
2. webアプリを動かすのにDBエンジンが必要。インストールしたら初期設定をする。
3. ソケット通信ができなかった。自分のソケット環境をtestの所に記述してなかった。