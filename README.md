# GitHub Copilot

本デモアプリでは To-Do アプリを途中から実装することを想定して作成しています。
未完成状態の To-Do アプリを Copilot を使って素早く開発してみましょう！

## Copilotでできること

- コメントからコード/SQL生成
- 文脈から関数や次の行をオートコンプリート
- 知識検索（APIまたはライブラリコール）
- コードからコメント生成


### コメントからコード/SQL生成

- `./routes/api.js` にコメントを記載すると自動でAPIが作成される
- `./lib/database/sql/DELETE_TASK.sql` にコメント記載すると自動で削除SQLが作成される

### 文脈から関数や次の行をオートコンプリート

- `./views/create.ejs' に他の項目を自動で推測して追加してくれる
- `./views/home.ejs` に改行を入れると自動で補完してくれる

### コードからコメント生成

- `./routes/create.js` の `GET: /` にはコメントがないが、実装から判断してコメントを入れてくれる

