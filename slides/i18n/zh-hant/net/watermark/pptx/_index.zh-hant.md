---
title: 通過 .NET 給 PPTX 文檔添加水印
weight: 5590
url: /zh-hant/net/watermark/pptx/ 
description: 用於在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上向 PPTX 文件添加或刪除水印的 C# 源代碼。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 將文本水印添加到 PPTX" h2="使用服務器端 API 構建您自己的 .NET 應用程序來為 PPTX 文件添加水印。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 給 PPTX 文件加水印" %}}

 為了給 PPTX 文件加水印，我們將使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API 是一個功能豐富、功能強大且易於使用的 C# 平台文檔操作 API。打開
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 **Aspose.Slides**
 並安裝。您還可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="通過 C# 向 PPTX 添加水印的步驟" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="您需要 [aspose.slides.dll](https://downloads.aspose.com/slides/net) 在您自己的環境中嘗試以下工作流程。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建 Presentation 類的實例
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
選擇主演示文稿
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 AddAutoShape 添加形狀類型
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 AddTextFrame 添加水印文本
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系統都支持 Aspose.Slides for .NET。只需確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或與 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系統。
- Microsoft Visual Studio 等開發環境。
- 項目中引用的 .NET 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="將水印添加到 PPTX - C#" offSpacer="" %}}

```cs

// create a Presentation from scratch
using (var presentation = new Aspose.Slides.Presentation())
{
    // get the Master Slide to add watermark on all slides
    var master = presentation.Masters[0];
    // add a new shape using IShapeColection.AddAutoShape
    var shape = master.Shapes.AddAutoShape(Aspose.Slides.ShapeType.Triangle, 0, 0, 0, 0);
    // set watermark text
    shape.AddTextFrame("CONFIDENTIAL");
    // save presentation in PPTX format
    presentation.Save("output.pptx", Aspose.Slides.Export.SaveFormat.Pptx);
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.Slides for .NET API" %}}

 Aspose.Slides API 可用於讀取、寫入、操作 Microsoft PowerPoint 文檔並將其轉換為 PDF、XPS、HTML、TIFF、ODP 和各種其他格式。可以從頭開始創建新文件並將其保存為相關支持的格式。 Aspose.Slides 是一個獨立的 API，用於創建、解析或操作演示文稿、幻燈片和元素，它不依賴於 Microsoft 或 OpenOffice 等任何軟件。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Watermark PPTX via Online App" sectionDescription="Add watermark to PPTX documents by visiting our [Live Demos website](https://products.aspose.app/slides/watermark). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PPTX file, set your watermark and hit \"Add\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" >}}
Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的水印格式" subTitle="使用 C#，可以輕鬆地為不同的格式添加水印，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/watermark/ppt/" name="PPT" description="微軟PowerPoint 97-2003" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}