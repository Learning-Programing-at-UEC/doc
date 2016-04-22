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

## linux
### RHEL 7/CentOS 7
```
wget https://packagecloud.io/github/git-lfs/packages/el/7/git-lfs-1.2.0-1.el7.x86_64.rpm/download -O git-lfs-1.2.0-1.el7.x86_64.rpm
yum localinstall git-lfs-1.2.0-1.el7.x86_64.rpm
git lfs install
```
### Debian 7
```
wget https://packagecloud.io/github/git-lfs/packages/debian/wheezy/git-lfs_1.2.0_amd64.deb/download -O git-lfs_1.2.0_amd64.deb
dpkg -i git-lfs_1.2.0_amd64.deb
git lfs install
```
***
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

# 詳しい使い方
公式マニュアル:
https://git-scm.com/book/ja/v2

おすすめサイト:
LearnGitBranching: http://pcottle.github.io/learnGitBranching
tryGit: http://try.github.io/


# GUIを使ってやりたい方

適当に情報を探してやってみてください
