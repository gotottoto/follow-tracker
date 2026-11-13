# FOLLOW TRACKER

Instagramの自分のアカウントのフォロー関係を、Instagram公式データのZIPから端末内で照合するPWAです。

## 機能
- 2アカウントを切り替えて個別管理
- 相互フォロー / フォロー中のみ / フォロワーのみを自動分類
- ユーザー名検索とInstagramプロフィールへのリンク
- 再読み込み時に前回の件数を履歴として保存
- ブラウザのlocalStorageに保存。ZIP自体は送信しません
- iPhoneのSafariからホーム画面に追加可能

## 使い方
1. Instagramのアカウントセンターから個人データをダウンロード
2. 対象アカウントのフォロワーとフォロー中を選択し、形式をJSONにしてダウンロード
3. ZIPを解凍せず、このアプリの該当アカウントで読み込む
4. 3つのタブで関係を確認する

## GitHub Pages
Repository Settings → Pages → Build and deployment → Deploy from a branch → main / root を選択。

公開URL: https://gotottoto.github.io/follow-tracker/

## 注意
- Instagramのログイン情報は不要・保存しません。
- Instagramのエクスポート形式の変更により読み込み形式が変わる場合があります。
- データはブラウザ内に保存されます。同じiPhone・同じブラウザで利用してください。ブラウザデータを消去すると保存内容も消えます。
- JSZipはCDNから読み込みます。ZIP解析時はインターネット接続が必要です。
- このアプリはフォロー解除などの操作を自動実行しません。
