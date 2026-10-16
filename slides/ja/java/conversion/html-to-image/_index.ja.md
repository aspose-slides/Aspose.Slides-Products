---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java で HTML を Image に変換する
url: /ja/java/conversion/html-to-image/
keywords: HTML から Image へ、HTML から Image への変換、Java API、Java ライブラリ、HTML、Image
description: Java で HTML を Image に変換します。 Java ライブラリ API を使用して HTML ファイルを Image ファイルに変換します
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で HTML を Image に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのJavaライブラリ。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java を使用して HTML を Image に変換します" variant="code" %}}

HTML を Image に変換するには、HTML ファイルからプレゼンテーションを作成し、Image として保存する必要があります。

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML を Image に変換する Java コード" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    FileInputStream tr = new FileInputStream("file.html");
    pres.getSlides().addFromHtml(tr);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        IImage image = slide.getImage(size);
        image.save("image_java_" + index + ".png", ImageFormat.Png);
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java で HTML を Image に変換する" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) は、プレゼンテーション ファイルを作成および操作するための強力な Java ライブラリです。さらに、HTML を Image に柔軟に変換する方法を提供します。 **Aspose.Slides for Java** を使用すると、開発者やアプリケーションは、わずか数行の Java コードで HTML ファイルを Image ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for Java は、HTML ファイルを Image ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、HTML を Image やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Aspose.Slides for Java API を使用して HTML を Image に変換する方法" intro="これらは、Java で HTML を Image に変換する手順です。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) をインストールします。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリ参照を Java プロジェクトに追加 (ライブラリをインポート) します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ソース HTML ファイルを Java で開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果を Image ファイルとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="無料のオンラインコンバーター"
  description="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="HTML を他のサポートされている形式に変換する" subTitle="HTML を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-xml/" name="HTML TO XML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
