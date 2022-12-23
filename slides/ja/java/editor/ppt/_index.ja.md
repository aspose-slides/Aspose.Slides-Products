---
title: JavaでPPTを編集
url: /ja/java/editor/ppt/
keywords: PPT の編集、PowerPoint の編集、PPT、PowerPoint、Java API、Java ライブラリ
description: Java で PPT を編集します。 Java ライブラリ API を使用して PowerPoint プレゼンテーションを編集する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="JavaでPPTを編集" h2="Java コードを使用して PPT を編集するための高速でクロスプラットフォームの Java ライブラリ" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して PPT を編集する" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) は、プレゼンテーションの操作と編集に使用される強力な Java ライブラリです。新しいテキスト行を追加することで、PPT プレゼンテーションを編集できます。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="JavaでPPTを編集" %}}
[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) を使用すると、わずか数行のコードで新しいテキスト行を PPT ドキュメントに追加できます。

{{% blocks/products/pf/agp/code-block title="PPT を編集するための Java コード" offSpacer="true" %}}
```java

Presentation pres = new Presentation("pres.ppt");
try {
    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("pres.ppt", SaveFormat.Ppt);
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="JavaでPPTを編集する方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** をインストールします。 [**インストール**](https://docs.aspose.com/slides/java/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリを参照としてプロジェクトに追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーション クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
編集する PPT プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
新しいテキスト行を追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
変更した PowerPoint ファイルを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/editor/html/" name="Edit HTML" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}