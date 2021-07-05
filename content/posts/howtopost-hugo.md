---
title: "Obisdianで編集した.mdファイルをGitでリモートリポジトリにpushしてHugoで変換してNetlifyでpostする流れ(自分用メモ)"
date: 2021-07-06T04:01:11+09:00
---

## 手順
1. pathを指定してディレクトリを変更
2. Hugoで新しいMarkdownファイルを作成
3. Obsidianでファイルを編集
4. Hugoでサイトを構築
5. Gitでリモートリポジトリにpush

##  commands
```bash
cd hugo/example/
hugo new posts/example.md

hugo -D
git add .
git commit -m "commit changes"
git push -u origin main
```

