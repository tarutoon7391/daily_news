# daily_news

## ワークフロー更新タスクの状況

**確認日時：** 2026年2月21日

### PR #3「news.yml の修正」の状況

| 項目 | 内容 |
|------|------|
| タイトル | Fix news.yml: robust multi-line env vars, correct auth header, proper Discord newlines |
| 状態 | オープン（未マージ） |
| 種別 | ドラフト |

**主な修正内容：**
- 複数行の環境変数を `$GITHUB_ENV` に正しく書き込むための heredoc 形式への変更
- `Authorization` ヘッダーの不正なクォートを修正
- Discord メッセージの改行を `printf` で正しく処理するよう変更
- 不要な `xmlstarlet` パッケージの削除

**結論：** ワークフロー更新タスク（PR #3）は現在もオープン状態のため、まだ完了していません。レビューおよびマージをお願いします。