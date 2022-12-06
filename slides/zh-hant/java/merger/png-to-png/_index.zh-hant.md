---
title: 在 Java 中合併 PNG 圖像
url: /zh-hant/java/merger/png-to-png/
keywords: 合併 PNG、PNG 到 PNG、合併 PNG、合併 PNG、Java API、Java 庫
description: 在 Java 中將 PNG 合併為 PNG。使用 Java 庫 API 合併 PNG 文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中合併 PNG" h2="用於使用 Java 代碼合併 PNG 圖像的高速跨平台 Java 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 PNG 合併為 PNG" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 是一個功能強大的 Java 庫，用於合併和操作演示文稿、圖像和其他文件。將 PNG 合併為 PNG 時，實際上是將兩張圖像組合成一張圖片。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Java 中將 PNG 合併為 PNG" %}}
使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/)，只需幾行代碼即可快速合併 PNG 文件

{{% blocks/products/pf/agp/code-block title="將 PNG 合併為 PNG 的 Java 代碼" offSpacer="true" %}}
```java

Presentation pres = new Presentation();
try {
    IPPImage image1 = pres.getImages().addImage(Files.readAllBytes("image1.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 100, 100, image1);

    IPPImage image2 = pres.getImages().addImage(Files.readAllBytes("image2.png"));
    pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 200, 100, 100, image2);

    for (int index = 0; index < pres.getSlides().size(); index++)
    {
        ISlide slide = pres.getSlides().get_Item(index);
        BufferedImage bufferedImage = slide.getThumbnail();
        ImageIO.write(bufferedImage, "PNG", new File("image_java_" + index + ".png"));
    }
} finally {
    if (pres != null) pres.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 Java 中合併 PNG" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝**Aspose.Slides for Java**。請參閱 [**安裝**](https://docs.aspose.com/slides/java/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要合併為相框的 PNG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 PNG 圖像。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="合併其他文件" subTitle="您還可以合併其他格式的文件以獲得單個文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}