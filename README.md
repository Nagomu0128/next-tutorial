Counter コンポーネント
  │
  ├─ RSC Payload（サーバーで生成）
  │    └─ 初期 HTML: <button>0</button>
  │    └─ 配置情報: "ここに Counter を置く"
  │    └─ 初期 props の値
  │
  └─ JS バンドル（クライアントに送信）
       └─ useState の定義
       └─ handleClick の定義
       └─ Hydration 後のレンダリングロジック