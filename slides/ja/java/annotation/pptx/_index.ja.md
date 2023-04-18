---
title: Java を使用して PPTX 注釈を削除する
weight: 360
url: /ja/java/annotation/pptx/ 
description: JSP/JSF アプリケーションおよびデスクトップ アプリケーションの Java ランタイム環境で PPTX 形式のアノテーションを削除する Java サンプル コードです。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java で PPTX からコメントとコメント作成者を削除する" h2="サーバー側 API を使用して、独自の Java アプリを構築し、ドキュメント ファイル内のコメントと作成者を操作します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{% blocks/products/pf/feature-page-section  h2="Java 経由で PPTX からコメントを削除する" %}}
PPTX ファイルから注釈を削除するには、[Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) API を使用します。これは、機能が豊富で強力で使いやすい API です。 Java プラットフォーム用のドキュメント操作 API。
{{% blocks/products/pf/agp/code-block title="PPTX から注釈を削除する - Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("example.pptx");
try {
    // Deletes all comments from the presentation
    for (ICommentAuthor author : presentation.getCommentAuthors())
    {
        author.getComments().clear();
    }

    // Deletes all authors
    presentation.getCommentAuthors().clear();

    presentation.save("example_out.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Java 経由で PPTX からコメントを削除する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Java** をインストールします。 [**インストール**](https://docs.aspose.com/slides/java/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation クラスのインスタンスを使用して PPTX をロードする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
読み込まれた PPTX のすべての作成者を反復処理します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
著者のすべてのコメントを削除する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最後にすべての作成者を削除します
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他の注釈形式" subTitle="Java を使用すると、次のような他の形式に簡単に注釈を付けることができます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}