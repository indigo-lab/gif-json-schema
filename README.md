# gif-json-schema

本リポジトリは、IPA（情報処理推進機構）により MIT ライセンスで公開されている [GIF コンポーネントツール](https://imi.go.jp/goi/gif) の一部、特に [政府相互運用性フレームワーク（GIF）](https://www.digital.go.jp/policies/data_strategy_government_interoperability_framework) に関する JSON スキーマを取り込み、
同フレームワークの仕様をより使いやすくするための試行・検証を行うことを目的としています。

これらの活動を通じて、GIF 仕様の理解促進および改善提案を行い、公式仕様へのフィードバックを目指します。

## Files

### docs/schema/

GIF コンポーネントツールに同梱されている `dev-gif-component-tools-schema-1.0.0.tgz` には
GIF に関わる JSON Schama 群が収録されています。

このフォルダではこれらの JSON Schema 群を変更せずに収録しています。

`dev-gif-component-tools-schema-1.0.0.tgz` の README.md から各ファイルに関する説明を抜粋します。

```
## schema/all.schema.json

- 任意の GIF JSON を validate することを目的とした汎用 JSON Schema です
- リテラルは type / enum / pattern のみで判定されます

## schema/${className}.schema.json

- 特定のクラスの GIF JSON を validate することを目的とした JSON Schema です
- リテラルは type / enum / pattern のみで判定されます

## schema/all.semantic.schema.json

- 任意の GIF JSON を validate することを目的とした汎用 JSON Schema です
- リテラルは format で判定されます
- format にはプロパティ名がアサインされます
- 動作のためには使用する JSON Schema Validator に対してカスタム Format の登録が必要です

## schema/${className}.schema.json

- 特定のクラスの GIF JSON を validate することを目的とした JSON Schema です
- リテラルは format で判定されます
- format にはプロパティ名がアサインされます
- 動作のためには使用する JSON Schema Validator に対してカスタム Format の登録が必要です
```

### docs/schema-for-humans/

各クラスごとに整備された `schema/${className}.schema.json` をソースとして、
[json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) で処理するために
改変を行った JSON Schema 群です。

### docs/html/

`docs/schema-for-humans/` のスキーマ群を `json-schema-for-humans` で処理して生成された HTML 群です。

## GitHub Pages

docs 配下の情報は GitHub Pages を通じてアクセス可能です。エントリポイントはこちらです。

- <https://indigo-lab.github.io/gif-json-schema/>

## License

本レポジトリのうち、 `docs/schema` のスキーマ群は IPA（情報処理推進機構）により MIT ライセンスで公開されている [GIF コンポーネントツール](https://imi.go.jp/goi/gif) の一部をコピーしたものです。

それ以外のリソースは [indigo-lab](https://github.com/indigo-lab) によって MIT ライセンスにて公開します。
