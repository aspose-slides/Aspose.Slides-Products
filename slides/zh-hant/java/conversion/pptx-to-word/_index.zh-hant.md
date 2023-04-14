---
title: 在 Java 中將 PPTX 轉換為 Word
url: /zh-hant/java/conversion/pptx-to-word/
keywords: 將 PPTX 轉換為 Word、將 PPTX 轉換為 Word、將 PPTX 轉換為 DOC、將 PowerPoint 轉換為 Word、Java API、Java 庫
description: 在 Java 中將 PPTX 轉換為 Word。使用 Java 庫 API 將 PowerPoint 轉換為 Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中將 PPTX 轉換為 Word" h2="強大的跨平台 Java API，無需 Microsoft PowerPoint 或 Office 即可使用 Java 代碼將 PowerPoint 轉換為 Word" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 和 Aspose.Words 將 PowerPoint 轉換為 Word" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 和 [**Aspose.Words for Java**](https://products.aspose.com/ words/java/) 是功能強大的 Java 庫，用於操作和轉換 PowerPoint 演示文稿、Word 文檔和其他文件。將 PowerPoint 轉換為 Word 時，實際上是將演示文稿幻燈片的內容移動到 Word 文檔中的頁面。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 Java 中將 PowerPoint 轉換為 Word" %}}
只需幾行代碼，您就可以快速將PPTX轉換成Word

{{% blocks/products/pf/agp/code-block title="將 PowerPoint 轉換為 Word 的 Java 代碼" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="如何將 PPTX 轉換為 Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝 **Aspose.Slides for Java** 和 **Aspose.Words for Java** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建 Presentation 類和 Doc 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要轉換為 Word 的 PPTX 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
根據幻燈片的內容生成圖像和文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 Word 文檔。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 PowerPoint 轉換為其他格式的文件" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-pdf/" name="PPTX TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}