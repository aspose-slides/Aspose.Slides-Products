---
title: 通过 C++ 应用程序将 ODP 转换为 PPSX
weight: 6290
url: /zh/cpp/conversion/odp-to-ppsx/ 
description: ODP 文档到 PPSX 格式的示例 C++ 转换代码。使用示例代码在任何 C++ 应用程序中进行批量 ODP 到 PPSX 的转换。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 ODP 转换为 PPSX" h2="使用 C++ 库的高性能 ODP 到 PPSX 转换，无需安装 Microsoft PowerPoint。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 ODP 转换为 PPSX" %}}

 为了将 ODP 转换为 PPSX，我们将使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp)
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

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 ODP 转换为 PPSX 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 ODP 文件转换为 PPSX。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Aspose.Slides 为 C++ 演示对象加载 ODP 文件。
1. 调用 Save() 方法。
1. 传递带有 (PPSX) 文件扩展名的输出文件路径。
1. PPSX 文件将保存在指定路径。
1. 在兼容程序中打开 PPSX 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有适用于 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境的兼容操作系统。
- 项目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODP 到 PPSX C++ 转换源代码" offSpacer="" %}}

```cs
// Load the ODP.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.odp");
// Save in PPSX format.
prs->Save(u"convertedFile.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="odp-to-ppsx"
        sectionTitle="免費應用程序將ODP轉換為PPSX" 
        sectionDescription="[嘗試我們的免費Video app](https://products.aspose.app/slides/video/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 ODP 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-bmp/" name="ODP TO BMP" description="位图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-emf/" name="ODP TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-gif/" name="ODP TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-html/" name="ODP TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pdf/" name="ODP TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-png/" name="ODP TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-potm/" name="ODP TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pps/" name="ODP TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-ppt/" name="ODP TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptm/" name="ODP TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-pptx/" name="ODP TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-svg/" name="ODP TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-tiff/" name="ODP TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-xml/" name="ODP TO XML" description="可扩展标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/odp-to-xps/" name="ODP TO XPS" description="XML 纸张规格" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}