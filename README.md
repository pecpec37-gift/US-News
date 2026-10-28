# 朝5分USニュース

米国の政府機関・FRB・議会・裁判所などの公式発表（一次情報）をもとに、重要な時事ニュースを毎朝5分で読める日本語ダイジェストにまとめるスマホ向けアプリです。TomTom TOWNS の一員です。

- 公開URL: https://pecpec37-gift.github.io/US-News/
- 毎朝 6:00ごろ（日本時間）、Claude の定期タスクが新しい号を追加します。

## データ

- `data/index.json` … 号の一覧（新しい順、最大30号）
- `data/editions/YYYY-MM-DD.json` … 各号の本文

`items[].cat` は `exec`（大統領・行政）`congress`（議会）`court`（司法）`econ`（経済・金融）`diplo`（外交・安全保障）`trade`（通商・規制）。`items[].jp` は日本への影響、`items[].primary` は一次情報（公式発表）のURLです。
