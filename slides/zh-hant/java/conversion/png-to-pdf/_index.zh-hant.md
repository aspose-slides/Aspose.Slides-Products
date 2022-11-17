---
title: 在 Java 中將 PNG 轉換為 PDF
url: /zh-hant/java/conversion/png-to-pdf/
keywords: PNG 到 PDF，將 PNG 轉換為 PDF，Java API，Java 庫，PNG，PDF
description: 在 Java 中將 PNG 轉換為 PDF。使用 Java 庫 API 將 PNG 文件轉換為 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中將 PNG 轉換為 PDF" h2="高速和跨平台的 Java 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Java 中將 PNG 轉換為 PDF" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 是一個強大的 Java 庫，用於創建和操作演示文稿文件。此外，它提供了將 PNG 轉換為 PDF 的靈活方法。使用**Aspose.Slides for Java**，任何開發人員或應用程序只需幾行 Java 代碼就可以將 PNG 轉換為 PDF 文件。

作為現代文檔處理API，Aspose.Slides for Java 可快速將PNG 文件導出為PDF 文件格式。 Aspose PowerPoint 庫允許您將 PNG 轉換為 PDF 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 將 PNG 轉換為 PDF" %}}
要將 PNG 轉換為 PDF，您需要從 PNG 文件創建演示文稿並將其另存為 PDF。

{{% blocks/products/pf/agp/code-block title="將 PNG 轉換為 PDF 的 Java 代碼" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    ISlide slide = pres.getSlides().get_Item(0);
	IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
	slide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.save("index.pdf", SaveFormat.Pdf);
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Java API 將 PNG 轉換為 PDF" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Java 中將 PNG 轉換為 PDF 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 Java 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 Java 中打開源 PNG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 PNG 轉換為其他支持的格式" subTitle="您還可以轉換 PNG 並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/png-to-jpg/" name="PNG TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/png-to-svg/" name="PNG TO SVG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}