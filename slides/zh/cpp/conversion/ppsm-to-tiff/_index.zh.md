---
title: 通过 C++ 应用程序将 PPSM 转换为 TIFF
weight: 5010
url: /zh/cpp/conversion/ppsm-to-tiff/ 
description: PPSM 文档到 TIFF 格式的示例 C++ 转换代码。在任何 C++ 应用程序中使用示例代码进行批量 PPSM 到 TIFF 的转换。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 PPSM 转换为 TIFF" h2="无需安装 Microsoft PowerPoint 即可使用 C++ 库进行高性能 PPSM 到 TIFF 转换。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 PPSM 转换为 TIFF" %}}

 为了将 PPSM 转换为 TIFF，我们将使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/)
 API 是一个功能丰富、功能强大且易于使用的 C++ 平台文档操作和转换 API。可以直接下载最新版本，直接打开
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 包管理器，搜索
 Aspose.Slides.Cpp
 并安装。您也可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 PPSM 转换为 TIFF 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 PPSM 文件转换为 TIFF。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Aspose.Slides for C++ Presentation Object 加载 PPSM 文件。
1. 调用 Save() 方法。
1. 传递带有 (TIFF) 文件扩展名的输出文件路径。
1. TIFF 文件将保存在指定路径。
1. 在兼容程序中打开 TIFF 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有适用于 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境的兼容操作系统。
- 项目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSM 到 TIFF C++ 转换源代码" offSpacer="" %}}

```cs
// Load the PPSM.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsm");
// Save in TIFF format.
prs->Save(u"convertedFile.tiff", Aspose::Slides::Export::SaveFormat::Tiff);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="免費應用程序將PPSM轉換為TIFF" 
        sectionDescription="[嘗試我們的免費Collage app](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 PPSM 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-bmp/" name="PPSM TO BMP" description="位图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-emf/" name="PPSM TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-html/" name="PPSM TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-png/" name="PPSM TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-xml/" name="PPSM TO XML" description="可扩展标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML 纸张规格" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}