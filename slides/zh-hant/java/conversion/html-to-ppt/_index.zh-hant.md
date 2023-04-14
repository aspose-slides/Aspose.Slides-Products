---
title: 在 Java 中將 HTML 轉換為 PPT
url: /zh-hant/java/conversion/html-to-ppt/
keywords: 將 HTML 轉換為 PPT、將 HTML 轉換為 PPT、PowerPoint、HTML、PPT、Java API、Java 庫
description: 在 Java 中將 HTML 轉換為 PPT。使用 Java 庫 API 將 HTML 轉換為 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 Java 中將 HTML 轉換為 PPT" h2="強大的跨平台 Java API，用於使用 Java 代碼將 HTML 轉換為 PPT" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將 HTML 轉換為 PPT" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/) 是一個功能強大的 Java 庫，用於創建、轉換和操作 PowerPoint 演示文稿、PDF、HTML 文檔和其他文件。將 HTML 轉換為 PPT 時，實際上是將 HTML 文檔中的內容移動到 PowerPoint 演示文稿中的幻燈片。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 Java 中將 HTML 轉換為 PPT" %}}
使用 [**Aspose.Slides for Java**](https://products.aspose.com/slides/zh-hant/java/)，您只需幾行代碼就可以將 HTML 文檔轉換為 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="HTML轉PPT的Java代碼" offSpacer="true" %}}
```java
Presentation presentation = new Presentation();
try {
    FileInputStream htmlStream = new FileInputStream("page.html");
    try {
        presentation.getSlides().addFromHtml(htmlStream);
    } finally {
        if (htmlStream != null) htmlStream.close();
    }

    presentation.save("Presentation.ppt", SaveFormat.Ppt);
} catch(IOException e) {
} finally {
    if (presentation != null) presentation.dispose();
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在Java中將HTML轉換為PPT" >}}


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
加載要轉換為 PPT 的 HTML 文檔。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將生成的文件另存為 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 轉換" subTitle="您還可以將其他格式的文件轉換為 PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/jpg-to-ppt/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/jpg-to-pptx/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}