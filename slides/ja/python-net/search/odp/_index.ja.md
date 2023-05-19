---
title: Python を使用して ODP プレゼンテーション ファイル内のテキストを検索
url: /ja/python-net/search/odp/
keywords: ODP で単語を検索、ODP でテキストを検索および置換、テキスト ODP を検索
description: ODP プレゼンテーション内のテキストを検索するための Python ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python を使用してテキスト ODP を検索" h2="独自の Python アプリを構築し、サーバー側 API を使用してプレゼンテーション ファイル内のテキストを検索および置換します。プレゼンテーション文書内の特定の単語またはフレーズのすべての入り口を見つける方法を学びます。正確なデータ一致と正規表現一致によりテキストを検索します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python 経由のテキスト ODP プレゼンテーションの検索と置換" %}}
Aspose.Slides for Python via .NET API を使用した基本的なドキュメントの検索と、コンテンツ、コメント、スライド ノート、またはメタデータ内のテキストの置換は、わずか数行のコードで実行できます。正規表現の一致、大文字と小文字の一致を使用して、プレゼンテーション内のテキストを検索します。タイトル、コンテンツ、フッター、またはヘッダー内のテキストを検索します。
{{% blocks/products/pf/agp/code-block title="Python を使用して、テキスト ODP プレゼンテーションを検索します" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.odp") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 経由で ODP のテキストを検索する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、テキスト ODP ファイルを検索する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスを使用して ODP を読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) メソッドを使用して、テキストを検索して置換します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を ODP 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="オンライン ODP 検索ライブ デモ" sectionDescription="今すぐ、ODP ドキュメントのコンテンツ、コメント、またはメタデータ内のテキストを検索して置換します。" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている検索形式" subTitle="Python を使用すると、次の形式でテキストを検索することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}