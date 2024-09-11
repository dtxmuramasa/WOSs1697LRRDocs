# 導入プラグイン
- まだ[Honkit](https://github.com/honkit/honkit)に移行後、完全な互換性があるか確認できていません。

## Gitbook系プラグイン
- hide-published-with
	- https://www.npmjs.com/package/gitbook-plugin-hide-published-with
	- Gitbookへのpublishボタンを消します。
	- リポジトリなどは残っていないが、機能はする模様。
- -lunr, -search
	- https://www.npmjs.com/package/gitbook-plugin-lunr
	- https://www.npmjs.com/package/gitbook-plugin-search
	- 標準搭載されている検索エンジンを無効化します。
- search-pro-kui
	- https://www.npmjs.com/package/gitbook-plugin-search-pro-kui
	- あらゆるutf-8文字の検索に高度に対応した検索エンジンプラグイン。
	- これを導入しないと日本語の部分検索が一部うまくいかないことがある。
		- 例えば「環境構築」での検索で引っかかる文書が「構築」では引っかからなかったりなど。
- uml
	- https://www.npmjs.com/package/gitbook-plugin-uml
	- plantUMLを扱うためのプラグイン。
- expandable-chapters
	- https://www.npmjs.com/package/gitbook-plugin-expandable-chapters
	- サイドバーのメニューをCollapse/Expandできるツリービューにするプラグイン。
- include-codeblock
	- https://www.npmjs.com/package/gitbook-plugin-include-codeblock
	- ファイルの内容を展開してくれるマクロを提供するプラグイン。
- code-editor
	- https://www.npmjs.com/package/gitbook-plugin-code-editor
	- よくあるコードエディタとコードの実行結果が見られるアレ。
- code
	- https://www.npmjs.com/package/gitbook-plugin-code
	- 複数行のコード記述に行数を表示してくれるプラグイン。

# ライセンス
- 本テンプレートは[Honkit](https://github.com/honkit/honkit)のライセンスに準じています。
- [Apache License 2.0全文](https://github.com/dtxmuramasa/HonkitTemplate/blob/main/LICENSE)
- [MIT License全文](https://opensource.org/license/mit)
