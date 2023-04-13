---
title: JavaでPPTXをWordに変換
url: /ja/java/conversion/pptx-to-word/
keywords: PPTX を Word、PPTX を Word、PPTX を DOC、PowerPoint を Word、Java API、Java ライブラリに変換
description: PPTX を Java で Word に変換します。 Java ライブラリ API を使用して PowerPoint を Word に変換する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaでPPTXをWordに変換" h2="Microsoft PowerPoint や Office を使用せずに Java コードを使用して PowerPoint を Word に変換するための強力なクロスプラットフォーム Java API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides と Aspose.Words を使用して PowerPoint を Word に変換" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) および [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) は、PowerPoint プレゼンテーション、Word ドキュメント、およびその他のファイルを操作および変換するために使用される強力な Java ライブラリです。 PowerPoint を Word に変換すると、基本的にプレゼンテーションのスライドの内容が Word 文書のページに移動されます。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Java で PowerPoint を Word に変換する" %}}
わずか数行のコードで PPTX を Word にすばやく変換できます

{{% blocks/products/pf/agp/code-block title="PowerPoint を Word に変換する Java コード" offSpacer="true" %}}
```java
Presentation pres = new Presentation(inputPres);
try {
    Document doc = new Document();
    DocumentBuilder builder = new DocumentBuilder(doc);
    for (ISlide slide : pres.getSlides())
    {
        // generates and inserts slide image
        BufferedImage bitmap = slide.getThumbnail(1, 1);

        builder.insertImage(bitmap);

        // inserts slide's texts
        for (IShape shape : slide.getShapes())
        {
            if (shape instanceof AutoShape)
            {
                builder.writeln(((AutoShape)shape).getTextFrame().getText());
            }
        }

        builder.insertBreak(BreakType.PAGE_BREAK);
    }
    doc.save(outputDoc);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPTXをWordに変換する方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** と **Aspose.Words for Java** をインストールします。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation クラスと Doc クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word に変換する PPTX プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
スライドの内容に基づいて画像とテキストを生成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の Word ドキュメントを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PowerPoint を他の形式のファイルに変換することもできます" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}