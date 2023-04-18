---
title: 使用 .NET 刪除 PPTX 註釋
weight: 4380
url: /zh-hant/net/annotation/pptx/ 
description: 用於在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上刪除 PPTX 格式註釋的 C# 源代碼。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="在 C# 中從 PPTX 中刪除評論和評論作者" h2="構建您自己的 .NET 應用程序以使用服務器端 API 操作文檔文件中的評論和作者。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C# 從 PPTX 中刪除評論" %}}
為了從 PPTX 文件中刪除註釋，我們將使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh-hant/net) API，它功能豐富、功能強大且易於使用用於 C# 平台的文檔操作 API。
{{% blocks/products/pf/agp/code-block title="從 PPTX 中刪除註釋 - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="如何通過 C# 從 PPTX 中刪除評論" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 **Aspose.Slides for .NET**。請參閱 [**安裝**](https://docs.aspose.com/slides/net/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 類的實例加載 PPTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍歷加載的 PPTX 的所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
刪除作者的所有評論
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最後刪除所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的註釋格式" subTitle="使用 C#，可以輕鬆地註釋其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}