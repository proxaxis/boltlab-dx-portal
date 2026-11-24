# REPORTS

- f8c12c3 | AGENTS.md を作成. マークダウン記述ルールとタスク完了時のワークフローを定義.
- 324b344 | AGENTS.md に環境セクションを追加し docker host `tcp://localhost:2375` (DinD) を明記.
- d9c5c7f | AGENTS.md に非テキストファイルの扱いを追加. Google Drive フォルダへの配置と事前確認をルール化.
- 4c191ca | AGENTS.md に営業先関連データの集約先 file_id を追記.
- 29baad9 | AGENTS.md にタスク開始時のワークフロー (fetch と pull) を追加.
- dc2c6d2 | README.md を作成. 社内業務ポータルの概要や対象読者、技術スタック (静的サイトや Jamstack)、ディレクトリ構成を記載.
- 219d7d5 | AGENTS.md に AGENTS.md の更新ルールを追加. 確認後の追記とシークレット値の非記載を明記.
- bea9a04 | Google Drive MCP サーバーを OAuth (読み取り専用) で設定し `.devin/mcp_config.local.json` に登録. `.gitignore` にローカル MCP 設定を追加.
- 7ef7e53 | Drive フォルダの CSV 13 件を "営業リスト" シートへ反映. 会計系を "税理士・会計事務所" に統合し重複解消. 既存 87 行を補完更新、410 行を追加 (計 497 件). 件数集計の式を範囲拡張. OAuth スコープを drive.readonly+spreadsheets へ更新.
- 69f190d | 営業リストの Web URL 325 件について https 対応可否を実測し "HTTPSか？" 列に YES/NO を記入. 結果 YES 307 件、NO 18 件 (http のみ応答するサイト).
- 7afe6d7 | シート構成変更 (ヘッダー 1 行目、J 列が結果列) に合わせて再チェックし J 列へ記入. URL 332 件、YES 313 件、NO 19 件.
- 220675c | `296-murayama/` に murayama-clinic.net のリニューアルサイトを作成. 元サイトのコンテンツを踏襲した単一ページの静的サイト (index.html と styles.css).
- d00c11d | 元サイトの画像アセット (ロゴ、MCやUC マーク、外観写真、略地図、favicon) を `assets/` に配置してページへ反映.
- d75a4ee | 296-murayama を DADS (デジタル庁デザインシステム) 準拠にリスタイル. Sea プライマリ、Sumi グレー、Noto Sans JP、下線リンクやピル型ボタンを採用.
