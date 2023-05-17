---
title: 使用 Java 編輯 PPT 演示文件
url: /zh-hant/java/redaction/ppt/
keywords: 編輯 PPT，查找並替換 PPT 中的文本，更新 PPT 演示文稿
description: Java 源代碼，用於查找和替換 PPT 演示文稿中的文本。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Java 編輯 PPT" h2="構建您自己的 Java 應用程序，以使用服務器端 API 查找和替換演示文件中的文本。了解如何搜索和替換 PPT 演示文稿的內容、評論或元數據中的文本" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 編輯 PPT 演示文稿" %}}
只需幾行代碼即可使用 Aspose.Slides for Java API 搜索和替換內容、評論、幻燈片註釋或元數據中的文本。在 PowerPoint 和 OpenOffice 中查找和替換文本。通過正則表達式數據匹配在演示文稿中編輯文本、評論和元數據。
{{% blocks/products/pf/agp/code-block title="使用 Java 編輯 PPT 演示文稿" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 Java 編輯 PPT" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是編輯 PPT 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 PPT。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) 方法查找和替換文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 PPT 格式保存結果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="在線 PPT 編輯現場演示" sectionDescription="立即在 PPT 文檔的內容、評論或元數據中搜索和替換文本。" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的密文格式" subTitle="使用Java，您還可以編輯以下格式：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}