# 挨拶するアプリをGinで作る
## はじめに
各種ファイルを管理したいディレクトリに移動後、ターミナルから
```
$ mkdir gin_lesson && cd gin_lesson
$ go mod init hello_gin
```
go modでプロジェクト初期化をしておきましょう。<br>
v1.7.4のGinをインストール
```
$ go get github.com/gin-gonic/gin@v1.7.4
```
## アプリ概要
HTMLのフォームから名前を入力、そんな前を利用して挨拶を返してくれるアプリ<br>
簡単なやつ。<br>

## 