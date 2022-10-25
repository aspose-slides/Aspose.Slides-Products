---
title: Javaを使用してPDF、PPT、PPTX、およびその他の多くのファイル形式をマージします
url: /ja/java/merger/
keywords: マージ、結合、PowerPoint、プレゼンテーション、Java、Aspose
description: Java PPT、PPTX、ODP、PDF、PNG、JPG などの複数のファイルをマージします。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Powerpoint、PDF、PPT、またはその他のドキュメントを Java でマージする" h2="PPT、PPTX、PDF、PNG、JPEG、およびその他の形式をマージするための高速 Java ライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="Javaを使用してPPT、PPTX、PDFをマージ" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) は、プレゼンテーション ファイルを作成および操作するための強力な Java ライブラリです。さらに、複数の PPT/PPTX プレゼンテーションを柔軟に組み合わせることができます。あるプレゼンテーションを別のプレゼンテーションにマージすると、それらのスライドを効果的に 1 つのプレゼンテーションに結合して 1 つのファイルを取得します。 Aspose.Slides では、2 つのプレゼンテーションを異なる方法でマージできます。品質やデータの損失を心配することなく、プレゼンテーションをすべての形状、スタイル、テキスト、書式、コメント、アニメーションなどと結合できます。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java で PowerPoint プレゼンテーションをマージする" %}}
PowerPoint プレゼンテーションを結合するには、あるプレゼンテーションから別のプレゼンテーションにスライドを複製する必要があります。

{{% blocks/products/pf/agp/code-block title="Java を使用して PPTX ファイルをマージする" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java を使用してプレゼンテーションをスライド マスターと結合する" %}}
この Java コードは、複数のプレゼンテーションを 1 つに結合し、スライド マスター プレゼンテーション テンプレートからスタイルを適用する方法を示しています。そのため、結果のプレゼンテーションは同じソースの書式設定を保持し、別のプレゼンテーションのマスター スライドの書式設定を含みます。

{{% blocks/products/pf/agp/code-block title="Javaで複数のPPTを1つにマージ" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API を使用してプレゼンテーションをマージする方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、2 つの PPTX ファイルをマージし、結果を Java で PDF として保存する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/) をインストールします。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリ参照を Java プロジェクトに追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース PPTX ファイルを Java で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**addClone** メソッドを使用して PPTX ファイルを結合します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションを保存し、結果を単一の PDF ファイルとして取得します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="マージするその他のサポートされている形式" subTitle="他のファイル形式を組み合わせることもできます。以下のサポートされているその他の形式を参照してください。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}