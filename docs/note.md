## スクリーン

- ログイン
- トップスクリーン：お菓子APIのデータ一覧
  - https://sysbird.jp/toriko/
- お菓子詳細スクリーン
  - タベタボタン
  - 評価機能
    - リピする
    - コスパ
    - コメント
    - など

## メモ

- 評価のデータをFirebaseに保存
- お菓子ID(APIから取得)をデータと併せて保存

## タスク

- API叩いてプリント
  - Flutter http：https://pub.dev/packages/http
- cachiリストビュー in トップスクリーン
  - cachiクラス作成
  - cachiリストビューアイテム
    - 詳細ボタン
    - タベタボタン
      - 評価画面 (モーダル) 表示