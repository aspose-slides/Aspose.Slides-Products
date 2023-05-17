---
title: Python を使用して PPT プレゼンテーション ファイルを編集します
url: /ja/python-net/redaction/ppt/
keywords: PPT を編集し、PPT 内のテキストを検索して置換し、PPT プレゼンテーションを更新します
description: Python ソース コードは、PPT プレゼンテーション内のテキストを検索して置換します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python を使用して PPT を編集します" h2="独自の Python アプリを構築し、サーバー側 API を使用してプレゼンテーション ファイル内のテキストを検索および置換します。 PPT プレゼンテーションのコンテンツ、コメント、またはメタデータ内のテキストを検索および置換する方法を学びます" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python 経由で PPT プレゼンテーションを編集します" %}}
Aspose.Slides for Python via .NET API を使用した基本的なドキュメントの検索と、コンテンツ、コメント、スライド ノート、またはメタデータ内のテキストの置換は、わずか数行のコードで実行できます。 PowerPoint および OpenOffice でテキストを検索して置換します。正規表現データのマッチングにより、プレゼンテーション内のテキスト、コメント、メタデータを編集します。
{{% blocks/products/pf/agp/code-block title="Python を使用して PPT プレゼンテーションを編集します" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.ppt") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 経由で PPT を編集する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPT ファイルを編集する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスを使用して PPT を読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
[FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) メソッドを使用して、テキストを検索して置換します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPT 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="オンラインの PPT 編集ライブ デモ" sectionDescription="今すぐ、PPT ドキュメントのコンテンツ、コメント、またはメタデータ内のテキストを検索して置換します。" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている墨消し形式" subTitle="Python を使用すると、次の形式を編集することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}