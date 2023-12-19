# GitHubPages_test

GitHub Pagesを使って多言語化対応した静的Webサイト／コンテンツ管理を実施するテスト

## 流れ  
コンテンツ（マークダウン方式）がマージされたタイミングでgithub actionsが動いて静的ページを作る

## システム構成
- GitHub Pagesは静的 Web サイト構築ツールにJekyllを推奨
- テーマはminimal-mistakes
- Jekyllの多言語化プラグインにuntra/polyglotがあってそれを入れれば多言語化できる
