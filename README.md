# 社会科 授業サイト（歴史総合・世界史・地理総合）

GitHub Pages で公開する、社会科の授業用サイトです。1つのサイトの中で3教科を切り替えて使います。

## 構成
- `index.html` … サイト本体（章・講の構成、連絡事項、教材リンクのデータも中に含まれます）
  - 歴史総合（`rekishi`）… データの `chapters`
  - 世界史（`sekaishi`）… データの `sekai.chapters`
  - 地理総合（`chiri`）… データの `geo.chapters`
- `files/rekishi/`・`files/sekaishi/`・`files/chiri/` … 生徒に配る Word / PowerPoint / PDF などの教材ファイル（教科ごと）
- 教科を指定して開くには URL の末尾に `#rekishi`・`#sekaishi`・`#chiri` を付けます

## 更新のしかた
- 教材の追加・連絡事項の更新は、Claude（Claude Code）に依頼して行います。
- ファイルを `files/教科/` に置き、`index.html` 内のデータに登録すると、該当する講に「プリント」「スライド」ボタンが表示されます。

## 注意
- 無料の GitHub Pages ではリポジトリが公開になるため、`files/` に置いたファイルは URL を知っていれば誰でも取得できます。
- 解答入りの資料は授業後に置く、または置かない運用にしてください。
- 生徒の名前などの個人情報は置かないでください。
