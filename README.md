# Test-Repository
基本操作ができるようになったつもり\
各コマンドについては[こちら](https://qiita.com/trafford_777/items/b40135995de01ae95dc2)で満足できると思う

### 用語
* リモートリポジトリ
　<dt>GitHub上に作るあれ</dt>
* ローカルレポジトリ
　<dt>PC(ローカル環境)に作るそれ</dt>
___
### 何か言われた時の対応
    fatal: not a git repository (or any of the parent directories): .git
    
意味：初期セットアップの不備ですよ</br>
-> [対処方法](https://qiita.com/gosairei1207/items/701b7ae494b96db0f9a1 "Qiita")

___
### 作ったものをgitコマンドを使って上げたいとき
1. 上げたいものを用意
2. ユーザー登録をする
    ```
    $ git config --global user.name "buchimi0301"
    $ git config --global user.email "Lhvg8845@gmail.com"
    ```
3. `$ git init`する
4. 更新したいやつを選択(追加)する
    ```
    全部選択
    $ git add .
    指定して選択
    $ git add ファイル名かディレクトリ名
    ```
5. 変更箇所を記録する
    ```
    $ git commit -m "メッセージ"
    ```
6. 変更を上げる
    ```
    $ git push リモート名 ブランチ名
    ```
    ※ origin(登録したリモートリポジトリのURL)

<br/>

**ブランチをリポジトリにプッシュとか まだよく分からない**