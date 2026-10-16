---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java で HTML を PPTX に変換する
url: /ja/java/conversion/html-to-pptx/
keywords: HTML を PPTX に、HTML を PPTX に、PowerPoint、HTML、PPTX、Java API、Java ライブラリに変換
description: Java で HTML を PPTX に変換します。 Java ライブラリ API を使用して HTML を PowerPoint に変換する
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で HTML を PPTX に変換する" h2="Java コードを使用して HTML を PPTX に変換するための強力なクロスプラットフォーム Java API" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java で HTML を PPTX に変換する" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) を使用すると、わずか数行のコードで HTML ドキュメントを PowerPoint プレゼンテーションに変換できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="HTML を PPTX に変換するための Java コード" >}}
```java
Presentation presentation = new Presentation();
try {
    presentation.getSlides().removeAt(0);
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.pptx", SaveFormat.Pptx);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides を使用して HTML を PPTX に変換する" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) は、PowerPoint プレゼンテーション、PDF、HTML ドキュメントなどの作成、変換、操作に使用される強力な Java ライブラリです。ファイル。 HTML を PPTX に変換すると、基本的に HTML ドキュメントのコンテンツが PowerPoint プレゼンテーションのスライドに移動されます。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="JavaでHTMLをPPTXに変換する方法" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java** をインストールします。 [**インストール**](https://docs.aspose.com/slides/java/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリを参照としてプロジェクトに追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーション クラスのインスタンスを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX に変換する HTML ドキュメントを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}結果のファイルを PPTX プレゼンテーションとして保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="無料のオンラインコンバーター"
  description="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="サポートされているその他の PowerPoint 変換" subTitle="他の形式のファイルを PowerPoint に変換することもできます" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
