# minecraft-bedrock-status ver.1.5
## これは何？
minecraft bedrock edition のサーバーステータスを取得するプログラムです
## 使い方
ひとまず実行することで調べたいサーバーのIPとポートを聞かれるので入力してください
## 仕組み
などを参考にして minecraft のクライアントが送信しているパケットをsocketを使い送信し
戻り値を得ています
## アップデートログ
### ver.1.5
- 特定のパケットで(motd表記より手前に) `;` が含まれている場合に発生するエラーを修正しました
- 通常より少ないmotdの表示に対応しました
