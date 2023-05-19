---
title: 使用 Java 在 ODP 演示文件中搜索文本
url: /zh/java/search/odp/
keywords: 在 ODP 中搜索词，在 ODP 中搜索和替换文本，在 ODP 中搜索文本 Presentation
description: Java 源代码，用于在 ODP 演示文稿中搜索文本。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 Java 搜索文本 ODP" h2="构建您自己的 Java 应用程序，以使用服务器端 API 搜索和替换演示文稿文件中的文本。了解如何在演示文稿中查找特定单词或短语的所有入口。通过精确数据匹配和正则表达式匹配搜索文本。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 搜索和替换文本 ODP 演示文稿" %}}
只需几行代码即可使用 Aspose.Slides for Java API 搜索和替换内容、评论、幻灯片注释或元数据中的文本。使用正则表达式匹配、匹配大小写来搜索演示文稿中的文本。在标题、内容、页脚或页眉中搜索文本。
{{% blocks/products/pf/agp/code-block title="使用 Java 搜索文本 ODP 演示文稿" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通过 Java 搜索 ODP 的文本" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是搜索文本 ODP 文件的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 实例加载 ODP。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) 方法查找和替换文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 ODP 格式保存结果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="在线 ODP 搜索现场演示" sectionDescription="立即在 ODP 文档的内容、评论或元数据中搜索和替换文本。" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的搜索格式" subTitle="使用Java，您还可以搜索以下格式的文本：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}