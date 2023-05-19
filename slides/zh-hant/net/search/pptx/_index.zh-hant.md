---
title: 使用 .NET 在 PPTX 演示文件中搜索文本
url: /zh-hant/net/search/pptx/
keywords: 在 PPTX 中搜索單詞，在 PPTX 中搜索和替換文本，在 PPTX 中搜索文本 Presentation
description: C# 源代碼，用於在 PPTX 演示文稿中搜索文本。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="使用 C# 搜索文本 PPTX" h2="構建您自己的 .NET 應用程序，以使用服務器端 API 搜索和替換演示文稿文件中的文本。了解如何在演示文稿中查找特定單詞或短語的所有入口。通過精確數據匹配和正則表達式匹配搜索文本。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C# 搜索和替換文本 PPTX 演示文稿" %}}
只需幾行代碼即可使用 Aspose.Slides for .NET API 搜索和替換內容、評論、幻燈片註釋或元數據中的文本。使用正則表達式匹配、匹配大小寫來搜索演示文稿中的文本。在標題、內容、頁腳或頁眉中搜索文本。
{{% blocks/products/pf/agp/code-block title="使用 C# 搜索文本 PPTX 演示文稿" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 C# 搜索 PPTX 的文本" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是搜索文本 PPTX 文件的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 實例加載 PPTX。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) 方法查找和替換文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
以 PPTX 格式保存結果
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="在線 PPTX 搜索現場演示" sectionDescription="立即在 PPTX 文檔的內容、評論或元數據中搜索和替換文本。" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的搜索格式" subTitle="使用C#，您還可以搜索以下格式的文本：" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}