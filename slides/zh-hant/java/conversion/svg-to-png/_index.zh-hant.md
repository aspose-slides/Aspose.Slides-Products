---
title: 在 Java 中將 SVG 轉換為 PNG
url: /zh-hant/java/conversion/svg-to-png/
keywords: SVG 到 PNG，將 SVG 轉換為 PNG，Java API，Java 庫，SVG，PNG
description: 在 Java 中將 SVG 轉換為 PNG。使用 Java 庫 API 將 SVG 文件轉換為 PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中將 SVG 轉換為 PNG" h2="高速和跨平台的 Java 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 Java 中將 SVG 轉換為 PNG" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 是一個強大的 Java 庫，用於創建和操作演示文稿文件。此外，它提供了將 SVG 轉換為 PNG 的靈活方法。使用**Aspose.Slides for Java**，任何開發人員或應用程序只需幾行 Java 代碼就可以將 SVG 轉換為 PNG 文件。

作為現代文檔處理API，Aspose.Slides for Java 可快速將SVG 文件導出為PNG 文件格式。 Aspose PowerPoint 庫允許您將 SVG 轉換為 PNG 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 將 SVG 轉換為 PNG" %}}
要將 SVG 轉換為 PNG，您需要從 SVG 文件創建演示文稿並將其另存為 PNG。

{{% blocks/products/pf/agp/code-block title="將 SVG 轉換為 PNG 的 Java 代碼" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    String svgContent = new String(Files.readAllBytes(Paths.get("image.svg")));
    ISvgImage svgImage = new SvgImage(svgContent);
    IPPImage ppImage = pres.getImages().addImage(svgImage);
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 
			ppImage.getWidth(), ppImage.getHeight(), ppImage);
    Dimension size = new Dimension(960, 720);
    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail(size);
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for Java API 將 SVG 轉換為 PNG" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 Java 中將 SVG 轉換為 PNG 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Install [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Add a library reference (import the library) to your Java project.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Open the source SVG files in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Save result as PNG file.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 SVG 轉換為其他支持的格式" subTitle="您還可以轉換 SVG 並保存為其他文件格式。查看下面所有支持的格式" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}