# gif-json-schema

本リポジトリは、IPA（情報処理推進機構）により MIT ライセンスで公開されている [GIF コンポーネントツール](https://imi.go.jp/goi/gif) の一部、特に [政府相互運用性フレームワーク（GIF）](https://www.digital.go.jp/policies/data_strategy_government_interoperability_framework) に関する JSON スキーマを取り込み、
同フレームワークの仕様をより使いやすくするための試行・検証を行うことを目的としています。

これらの活動を通じて、GIF 仕様の理解促進および改善提案を行い、公式仕様へのフィードバックを目指します。

## Repository

この Web ページは <https://github.com/indigo-lab/gif-json-schema> で管理されています。
最新の情報はレポジトリの [README.md](https://github.com/indigo-lab/gif-json-schema) を確認してください。

## Contents

### JSON Schema

レポジトリで管理されている JSON Schema は以下のような URL でアクセス可能です。

- `https://indigo-lab.github.io/gif-json-schema/schema/*.schema.json`
- `https://indigo-lab.github.io/gif-json-schema/schema-for-humans/*.schema.json`

たとえば [Accesibility.schema.json](https://github.com/indigo-lab/gif-json-schema/blob/main/docs/schema/Accessibility.schema.json) とそのバリエーションは以下のような URL でアクセスできます。

- <https://indigo-lab.github.io/gif-json-schema/schema/Accessibility.schema.json>
- <https://indigo-lab.github.io/gif-json-schema/schema/Accessibility.semantic.schema.json>
- <https://indigo-lab.github.io/gif-json-schema/schema-for-humans/Accessibility.schema.json>

### HTML (experimental)

[schema-for-humans](https://github.com/indigo-lab/gif-json-schema/tree/main/docs/schema-for-humans) に配備されている JSON Schema 群を [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) で処理した HTML ファイルを提供しています。
JSON Schema の内容を HTML ビューで確認することができます。

**※ 実験的です。一部のファイルはサイズが大きいためご注意ください。**

- [Accessibility](./html/Accessibility.schema.html)
- [Address](./html/Address.schema.html)
- [Building](./html/Building.schema.html)
- [BusinessPlace](./html/BusinessPlace.schema.html)
- [ChildcareInformation](./html/ChildcareInformation.schema.html)
- [CodeInformationModel](./html/CodeInformationModel.schema.html)
- [ContactPoint](./html/ContactPoint.schema.html)
- [Equipment](./html/Equipment.schema.html)
- [Event](./html/Event.schema.html)
- [Facility](./html/Facility.schema.html)
- [IdInformationModel](./html/IdInformationModel.schema.html)
- [Land](./html/Land.schema.html)
- [LegalEntity](./html/LegalEntity.schema.html)
- [Person](./html/Person.schema.html)
- [RelatedOrganizationInformationModel](./html/RelatedOrganizationInformationModel.schema.html)
- [RoleInformationModel](./html/RoleInformationModel.schema.html)
