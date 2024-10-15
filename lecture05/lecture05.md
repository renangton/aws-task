## 第5回課題

### 組み込みサーバー（Puma）で確認
**起動画面**  
![](image/pumaonly-boot.png)  

**画面表示確認**  
![](image/pumaonly-browser.png)  

### 組み込みサーバーとUnix Socketで確認
**起動画面**  
![](image/puma-websocket-boot.png)  

**接続確認**  
![](image/puma-websocket-curl.png)  

### Nginxの単体起動確認
**起動画面**  
![](image/nginxonly-boot.png)  

**画面確認**  
![](image/nginxonly-browser.png)  

### Nginxと組み込みサーバ、UnixSocketで確認
**起動画面**  
![](image/puma-nginx-boot.png)  

**画面確認**  
![](image/puma-nginx-browser.png)  

### ALB追加確認
**DNS名確認**  
![](image/alb-dns.png)  

**画面確認**  
![](image/alb-browser.png)  

### S3追加確認
**画面確認**  
![](image/s3-browser.png)  

**S3コンソール確認（追加前）**  
![](image/s3-object-before.png)  

**S3コンソール確認（追加後）**  
![](image/s3-object-after.png)  

### 構成図
![](image/architecture-diagram.png)  

### 講座感想
ALBとS3の構築はスムーズにできましたが、EC2にサンプルアプリの環境を作るところでかなり苦戦しました。  
セキュリティグループの設定でハマったおかげで、セキュリティグループ周りの理解が深まったと思います。この調子でどんどん詰まりながらも解決して、AWS全体の理解をもっと深めていきたいです。
