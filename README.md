# git-tutorial

git の基本操作（clone / commit / push）をデモするためのリポジトリです。

## 基本コマンド

```bash
# リポジトリをクローン
git clone https://github.com/amex678/git-tutorial.git

# 変更をステージング
git add .

# コミット
git commit -m "feat: 変更内容を記述する"

# リモートにプッシュ
git push origin main
```

## ブランチ操作

```bash
# 新しいブランチを作成して切り替え
git checkout -b feature/my-branch

# ブランチ一覧を確認
git branch -a

# mainブランチにマージ
git checkout main
git merge feature/my-branch
```

## 状態確認

```bash
# 変更状態を確認
git status

# コミット履歴を確認
git log --oneline
```
