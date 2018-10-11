# Pleiades 誤訳トラッカー
Pleiades による IntelliJ や Eclipse の翻訳や JetBrains 製品のオンラインヘルプ日本語サイト https://pleiades.io の誤訳や問題を管理します。オンラインヘルプの原文は jetbrains.com から自動的に取得しており、翻訳後の著作権も jetbrains.com にあります。

## 誤訳などの報告・要望
[Issues](../../issues) から New Issue を作成してください。仕組上、以下の制限があります。
* 特定のページに対する指摘対応は、基本的にサイト全体 1万ページ超に渡って影響する
* 同じ英単語・文章に対して、異なるページで異なる訳にできない
* 翻訳禁止ワードも同じく全ページ共通（例えば Gradle や Spring のような単語は全ページで翻訳されない）
* オリジナルが数日おきに更新されていることもあり、今のところ多少変な箇所は放置し、明らかな誤訳を優先して対応

## 翻訳ポリシー
* 翻訳エンジンは [Pleiades](http://mergedoc.osdn.jp/) 辞書および、前編集、後編集、翻訳禁止辞書などの多くのルール辞書と Google 翻訳 API などにより構成されています。
* Pleiades 辞書は、私を含むプロジェクトメンバーで策定した[eclipse.org 翻訳ルール](https://wiki.eclipse.org/%E7%BF%BB%E8%A8%B3%E3%83%AB%E3%83%BC%E3%83%AB)が元になっていますが、内容はすでに古くなっており、現状にマッチしない部分があるため、改善されています。
* しかし、pleiades.io では Pleiades 辞書のみで解決できる UI 操作系のみ上記ルールとなっており、その他の部分は、このルールに則っていません。今後、全体的に整合性が取れるようなルールを適用する可能性があります。
