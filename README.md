# 家の在庫管理 PWA

## 使い方
1. このフォルダ一式をHTTPSで公開します。
   - GitHub Pages
   - Netlify
   - Cloudflare Pages
   などでOKです。

2. iPhoneのSafariで公開URLを開きます。

3. 共有ボタン →「ホーム画面に追加」を選びます。

4. 以後はホーム画面のアイコンから起動できます。

## 機能
- 在庫状態「ある / 少ない / ない」
- 買うものだけ表示
- カテゴリ絞り込み
- 品目追加 / 削除
- localStorageによる端末内保存
- Service Workerによるオフライン対応
- iPhoneホーム画面用アイコン
- ダークモード対応

## 注意
データは端末内(localStorage)に保存されます。
SafariのWebサイトデータを削除すると消える場合があります。
別端末とは自動同期しません。
