# GROWI Plugin Templates for Template

これはGROWIテンプレートプラグインのテンプレートです。

## 使い方

dist/example をコピーして、適当な名前にリネームしてください。

## exampleの内容

フォルダの内容は、ロケール（言語）フォルダがあり、その中に `meta.json` と `template.md` があります。

- meta.json  
一覧表示時のタイトルを設定します。
- template.md  
テンプレートとして選択した際に挿入される内容です。

## 注意点

- dist以下には複数のフォルダを配置できます（複数のフォルダが利用できます）。
- 日英以外のロケールを追加する場合は、package.jsonの `locales` キーに追加後、フォルダを追加してください。

# License

MIT