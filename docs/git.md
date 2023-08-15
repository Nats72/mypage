# Git
## インストール＆設定
RHEL8系の場合
```
# dnf -y install git
```
設定
```
# git config --global user.name {UserName}
# git config --global user.email {UserEmail}
```

## クローン
GitHubからリポジトリの設定とデータを初回ダウンロードしてくるコマンド。  
以下のコマンドを打つと、コマンドを打ったディレクトリの下に、`mypage`というディレクトリ(ローカルリポジトリ)が作成される。  
このリポジトリは、GitHub(リモートリポジトリ)と紐付けられている。  
```
# git clone https://github.com/Nats72/mypage.git
```

### (参考)リポジトリには.gitがある
ローカルリポジトリには、.gitという設定ファイルが保存された隠しディレクトリが保存されている。
```
# cd mypage/
# ls -la
合計 4
drwxr-xr-x. 3 root root  35  8月 15 01:01 .
drwxr-xr-x. 6 root root  59  8月 15 01:01 ..
drwxr-xr-x. 8 root root 163  8月 15 01:01 .git
-rw-r--r--. 1 root root   8  8月 15 01:01 README.md
```

```
# mkdir -p .github/workflows
# touch .github/workflows/run.yml
```

## プッシュ
```
# git add .
# git commit -m "first commit"
# git push origin main
```