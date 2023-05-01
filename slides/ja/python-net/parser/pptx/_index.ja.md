---
title: Python を使用して PPTX ファイルからテキストと画像を抽出する
url: /ja/python-net/parser/pptx/
keywords: Python を使用して PPTX を解析、PPTX パーサー Python、Python の PPTX からデータを抽出、Python を使用して PPTX からテキストを抽出、Python を使用して PPTX から画像を抽出
description: Python ソース コードを解析して PPTX プレゼンテーション。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python を使用して PPTX プレゼンテーションからテキストと画像を抽出する" h2="サーバー側 API を使用して、PowerPoint からテキスト、画像、ビデオ、およびオーディオ ファイルを抽出する独自の Python アプリを構築します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python 経由で PPTX プレゼンテーションからテキストを抽出" %}}
プレゼンテーション全体からテキストをスキャンするには、SlideUtil クラスによって公開される [GetAllTextFrames](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) 静的メソッドを使用します。以下のコードは、マスター スライドを含むプレゼンテーションからテキストと書式設定情報をスキャンします。
{{% blocks/products/pf/agp/code-block title="Python を使用して PPTX プレゼンテーションからテキストを抽出しています" offSpacer="true" %}}

```py

import aspose.slides as slides

#Instatiate Presentation class that represents a PPTX file
with slides.Presentation("pres.pptx") as pptxPresentation:
    # Get an Array of ITextFrame objects from all slides in the PPTX
    textFramesPPTX = slides.util.SlideUtil.get_all_text_frames(pptxPresentation, True)
    
    # Loop through the Array of TextFrames
    for i in range(len(textFramesPPTX)):
	    # Loop through paragraphs in current ITextFrame
        for para in textFramesPPTX[i].paragraphs:
            # Loop through portions in the current IParagraph
            for port in para.portions:
			    # Display text in the current portion
                print(port.text)

    			# Display font height of the text
                print(port.portion_format.font_height)

			    # Display font name of the text
                if port.portion_format.latin_font != None:
                    print(port.portion_format.latin_font.font_name)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 経由で PPTX からテキストを抽出する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="PPTX ファイルを解析する手順は次のとおりです。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPTX を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX 内のすべてのスライドから TextFrame オブジェクトの配列を取得します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
TextFrames の配列をループする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
現在の TextFrame の段落をループします
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
現在の段落の部分をループする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
現在の部分のテキストを取得する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他の解析形式" subTitle="Python を使用すると、次の形式もスキャンできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/parser/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/parser/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}