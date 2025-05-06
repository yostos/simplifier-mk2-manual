# ドキュメントディレクトリ

このディレクトリには、DSM Humboldt Simplifier MKIIのマニュアル翻訳プロジェクトに関連するドキュメントが含まれています。

## ディレクトリ構造

- `en/` - 英語のオリジナルマニュアル（AsciiDocソース）
- `ja/` - 日本語翻訳マニュアル（AsciiDocソース）
- `images/` - マニュアルで使用される画像ファイル

## リリース

コンパイル済みPDFファイルは、GitHubのリリースセクションからダウンロードできます。これにより、リポジトリサイズを最小限に保ちながら、完成したドキュメントを簡単に配布できます。

## ビルド手順

AsciiDocファイルからPDFをビルドするには：

```bash
# 英語版のビルド
asciidoctor-pdf docs/en/simplifier-mk2.adoc -o simplifier-mk2.pdf

# 日本語版のビルド
asciidoctor-pdf docs/ja/simplifier-mk2.adoc -o simplifier-mk2-j.pdf
```

詳細については、プロジェクトのルートディレクトリにあるREADME.mdファイルを参照してください。