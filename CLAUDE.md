# だるまサイト 作業メモ

## プロジェクト概要
- 店舗: 焼肉はひとくちめ だるま
- URL: https://hitokuchi-daruma.com（予定）
- ホスティング: GitHub Pages 予定
- リポジトリ: atmos-dining/daruma-site（未作成）
- ブランチ: main

## デザイン
- テーマカラー: 深紅 #8b1a1a + ゴールド #c9962e
- フォント: Noto Sans JP（モダンカジュアル）
- パターンB（白×深紅）

## 店舗情報
- 住所: 〒810-0042 福岡県福岡市中央区六本松3丁目8-4
- TEL: 092-707-1029
- 営業時間: 17:00〜翌1:00（L.O. 翌0:00）年中無休
- アクセス: 地下鉄七隈線「六本松駅」徒歩3分
- 席数: 72席（3フロア）
- Instagram: @hitokuchi_daruma
- 予約: Toreta（URLは要確認・現在プレースホルダー）

## ブログの仕組み
- ブログデータ: blog/posts.json（{ "posts": [...] }形式）
- 記事一覧: blog/index.html
- 記事詳細: blog/posts/post.html?slug=xxx
- 画像: images/ フォルダ

## CMS（Sveltia CMS）
- /admin でログイン
- GitHubリポジトリ atmos-dining/daruma-site が必要
- Cloudflare Worker（共用）: https://sveltia-cms-auth.atmos-nextgen-team.workers.dev

## TODO（初期セットアップ）
- [ ] GitHubリポジトリ atmos-dining/daruma-site 作成
- [ ] GitHub Pages 有効化
- [ ] 独自ドメイン設定（hitokuchi-daruma.com）
- [ ] Toretaの予約URL確認・差し替え（現在プレースホルダー）
- [ ] 店舗写真をJPGで書き出してimages/に差し替え
- [ ] Google Analytics タグ追加
- [ ] CNAME ファイル追加

## 写真（現在の状態）
- Bunta-site からの仮写真を使用中
- 実際の写真は /Volumes/JIS/アトモス/店舗写真/だるま/ にあり（PSD形式）
- 写真が揃い次第 images/ フォルダに差し替える
