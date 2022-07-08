---
name: db-design
about: DB設計用のissue
title: "[DB設計] 論理名（コレクション名）"
labels: ''
assignees: ''

---

### 作業内容

1. issueのサイドメニュー（右）にある`Projects`の`Status`を`In Progress`に変更（作業する前に変更してください）
2. `database` ブランチから作業ブランチを作成（作業ブランチ名は命名方針を参照）
3. 作業ブランチへ移動
4. DB定義書をもとにDBスキーマの定義を作成
5. 変更をコミット・プッシュ
6. Pull Requestを作成。Pull Requestのマージ先は`database`を指定

**命名方針**

 - 作業ブランチ名：feature/#{issue number}
 - 作業ブランチの派生元：`database`ブランチ
 - Pull Request名：feature/#{issue number} 論理名（コレクション名）
 - Pull Requestのマージ先：`database`ブランチ

**ドキュメント**
