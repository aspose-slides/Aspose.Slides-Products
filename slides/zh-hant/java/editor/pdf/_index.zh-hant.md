---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 Java 中編輯 PDF
url: /zh-hant/java/editor/pdf/
keywords: 編輯 PDF、PDF、Java API、Java 庫
description: 在 Java 中編輯 PDF。使用 Java 庫 API 編輯 PDF 文檔
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 Java 中編輯 PDF" h2="用於使用 Java 代碼編輯 PDF 的高速跨平台 Java 庫" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 Java 中編輯 PDF" variant="code" %}}

使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/)，您只需幾行代碼就可以向 PDF 文檔添加新的文本行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="編輯PDF的Java代碼" >}}
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

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 編輯 PDF" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 是一個功能強大的 Java 庫，用於操作和編輯演示文稿、PDF 文檔和其他文件。您可以通過向其中添加新的文本行來編輯 PDF 文檔。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 Java 中編輯 PDF" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安裝**Aspose.Slides for Java**。請參閱 [**安裝**](https://docs.aspose.com/slides/java/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加庫作為項目中的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}創建一個 Presentation 類的實例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加載要編輯的 PDF 文檔。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改後的 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="編輯其他文件" subTitle="您還可以編輯其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh-hant/java/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
