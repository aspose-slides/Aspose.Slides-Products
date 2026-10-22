---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: JavaでPDFを編集
url: /ja/java/editor/pdf/
keywords: PDF の編集、PDF、Java API、Java ライブラリ
description: Java で PDF を編集します。 Java ライブラリ API を使用して PDF ドキュメントを編集する
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="JavaでPDFを編集" h2="Java コードを使用して PDF を編集するための高速でクロスプラットフォームの Java ライブラリ" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="JavaでPDFを編集" variant="code" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) を使用すると、数行のコードで新しいテキスト行を PDF ドキュメントに追加できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PDF を編集するための Java コード" >}}
```java

Presentation pres = new Presentation();
try {
    pres.getSlides().removeAt(0);
    pres.getSlides().addFromPdf("document.pdf");

    ISlide slide = pres.getSlides().get_Item(0);
    IAutoShape shape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 50);
    shape.getTextFrame().setText("New text");

    pres.save("document.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides を使用して PDF を編集" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/ja/java/) は、プレゼンテーション、PDF ドキュメント、およびその他のファイルの操作と編集に使用される強力な Java ライブラリです。新しいテキスト行を追加して PDF ドキュメントを編集できます。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="JavaでPDFを編集する方法" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for Java** をインストールします。 [**インストール**](https://docs.aspose.com/slides/java/installation/) を参照してください。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ライブラリを参照としてプロジェクトに追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーション クラスのインスタンスを作成します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}編集する PDF ドキュメントを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}新しいテキスト行を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}変更した PDF ファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/ja/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
