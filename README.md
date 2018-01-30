Play-Scalaのサンプル

## 前提条件
ローカル環境: Git, Play, Scala, JDK, Eclipseがあること  
リモート: Git, Activator, Scala, JDK があること  

## 環境構築
### githubからクローン
```
任意の場所にフォルダを作成
→ フォルダ右クリック →Gitクローン
→ URLにhttps://github.com/wchikarusato/HelloPlayScala を入れてOK

コマンドプロンプト立ち上げる
  > cd クローンしたリポジトリ\HelloPlayScala\Application
  > play run
  ブラウザ起動してlocalhost:9000にアクセス→Welcome to Play表示されればok
```

### Eclipseにプロジェクト入れる
```
$ cd クローンしたリポジトリ\HelloPlayScala\Application
$ play eclipse

  Eclipse立ち上げる
  → Project Explorerの開いてる場所を右クリック → inport → Inport
  → existing projects でフィルタリング
  → Select root directory に上でplayコマンドした場所を指定してfinish
```

### リモートでプロジェクトデプロイ
```
$ git clone https://github.com/wchikarusato/HelloPlayScala
$ cd クローンしたリポジトリ\HelloPlayScala\Application
$ activator run
  ローカルでブラウザ立ち上げる
  →リモートの9000ポートにアクセス → ScalaPlayの画面が表示されればok
```

## 改修
### 編集中
