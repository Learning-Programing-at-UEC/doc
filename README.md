# プログラミング教室で使用する資料

プログラミング教室で使用する資料はこちらにコメットしてください

# ファイルの管理について

Git LFSを使ってドキュメントを管理していくので皆様使えるようにセットアップしておいてください。
***

# GitとGit LFSのインストール

## windows

https://git-scm.com/

インストーラーでインストール。コマンドプロンプトからも使えるように、途中「Use Git from the Windows Command Prompt」をチェック

https://git-lfs.github.com/

最後に、「git lfs init」と打つように出るので、OK を押す


## mac

homebrewからインストールすると楽なのでそちらを使ってください

インストールは以下のコマンドで大丈夫です

```shell:
brew install git
brew install git-lfs
```

****
# gitの使い方


## レポジトリのクローン

```
git clone githubのレポジトリ
```

# ファイルを更新したり追加したりした時

基本的には以下のコマンドをセットで使います

コミットした際はわかりやすいコメントを入れてください

```
git add .
git commit
git push
```

# GUIを使ってやりたい方

適当に情報を探してやってみてください
