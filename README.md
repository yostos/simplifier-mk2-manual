# Simplifier MKII Manual Translation Project

![Documentation](https://img.shields.io/badge/Documentation-Japanese_Translation-blue.svg)
![Status](https://img.shields.io/badge/Status-Published-green.svg)
![Copyright](https://img.shields.io/badge/Copyright-DSM%2FHUMBOLDT-red.svg)

## Overview

This repository is a project for translating the DSM Humboldt Simplifier
MKII user manual into Japanese. The original text is written in English, and
the aim is to provide an unofficial Japanese translation for users in Japan.

このリポジトリはDSM Humboldt Simplifier MKIIのユーザーマニュアルを日本語に翻訳するためのプロジェクトです。原文は英語で書かれており、日本のユーザー向けに非公式の日本語翻訳を提供することを目的としています。

## Documentation

This project includes the following documents (このプロジェクトには以下のドキュメントが含まれています)：

- **English Manual (AsciiDoc)** - `docs/en/simplifier-mk2.adoc` - Source
  AsciiDoc file for translation
- **Japanese Manual (AsciiDoc)** - `docs/ja/simplifier-mk2.adoc` - Source
  AsciiDoc file for Japanese translation

### How to Obtain PDF Manuals

Download the PDF files from the [latest release](https://github.com/yostos/simplifier-mk2-manual/releases/latest) ([最新のリリース](https://github.com/yostos/simplifier-mk2-manual/releases/latest)からPDFファイルをダウンロードしてください)

- Each version release includes the following PDFs:
  - `simplifier-mk2.pdf` - English manual
  - `simplifier-mk2-j.pdf` - Japanese manual

## About Translation

The Japanese translation aims to convey the content of the original text as
accurately as possible. For technical terms and explanations, we strive to
use common terminology in the Japanese music and audio equipment field.

The English PDF was created in AsciiDoc format from the official manual for the purpose of Japanese translation. The manuals in this repository are based on the official manual as of May 6, 2025.

日本語への翻訳は、原文の内容をできるだけ正確に伝えることを目指しています。専門用語や技術的な説明については、日本の音楽・オーディオ機器の一般的な用語を使用するよう努めています。

英語版のPDFは日本語翻訳のために公式マニュアルからasciidoc形式で作成したものです。本リポジトリのマニュアルは2025年5月6日時点の公式マニュアルを元にしています。

## Build Method (ビルド方法)

To generate PDFs from AsciiDoc source files, use AsciiDoctor PDF:

```bash
asciidoctor-pdf simplifier-mk2.adoc -o simplifier-mk2.pdf
asciidoctor-pdf simplifier-mk2-j.adoc -o simplifier-mk2-j.pdf
```

## Copyright and Disclaimer

## 著作権および免責事項

The copyright for the original text of this manual and all images and product information belongs to DSM/HUMBOLDT. This Japanese manual is an unofficial translation intended for private use and does not guarantee translation accuracy.

This repository has been created for personal learning and reference purposes only, and commercial use or redistribution is not permitted. In case of any discrepancy with official information from DSM/HUMBOLDT, always prioritize [the official information](https://www.dsmhumboldt.com/).

Unauthorized reproduction, redistribution, and commercial use are prohibited. For product purchases and official information, please refer to the official DSM/HUMBOLDT website.

本マニュアルの原文およびすべての画像、製品情報に関する著作権はDSM/HUMBOLDT社に帰属します。この日本語マニュアルはプライベート使用を目的とした非公式翻訳であり、翻訳精度について保証するものではありません。

このリポジトリは個人的な学習および参照目的のみに作成されたものであり、商用利用や再配布は許可されていません。DSM/HUMBOLDT社の公式情報とは異なる場合は、常に公式情報を優先してください。

無断複製・転載・商用利用は禁止されています。製品の購入や正式な情報については、DSM/HUMBOLDT社の[公式ウェブサイト](https://www.dsmhumboldt.com/)をご参照ください。

## Disclaimer

## 免責事項

This manual translation is provided "as is" without any warranty, express or implied. We assume no responsibility for any damages resulting from the use of this translated document. If there are any errors or unclear points in the translation, please refer to the [official English manual](https://www.dsmhumboldt.com/user-manuals).

このマニュアル翻訳は「現状のまま」提供され、明示または黙示を問わず、いかなる保証も行いません。この翻訳ドキュメントの使用によって生じるいかなる損害についても責任を負いません。翻訳の誤りや不明確な点がある場合は、[公式の英語マニュアル](https://www.dsmhumboldt.com/user-manuals)を参照してください。
