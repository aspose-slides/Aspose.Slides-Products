---
title: 通过 C++ 应用程序将 POT 转换为 BMP
weight: 5920
url: /zh/cpp/conversion/pot-to-bmp/ 
description: POT 文档到 BMP 格式的示例 C++ 转换代码。使用示例代码在任何 C++ 应用程序中进行批量 POT 到 BMP 的转换。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C++ 将 POT 转换为 BMP" h2="使用 C++ 库的高性能 POT 到 BMP 转换，无需安装 Microsoft PowerPoint。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C++ 将 POT 转换为 BMP" %}}

 为了将 POT 转换为 BMP，我们将使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)
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

{{% blocks/products/pf/agp/feature-section-col title="通过 C++ 将 POT 转换为 BMP 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 C++ 开发人员只需几行代码即可轻松地将 POT 文件转换为 BMP。

{{% /blocks/products/pf/agp/text %}}

1. 使用 Aspose.Slides 为 C++ 演示对象加载 POT 文件。
1. 选择第一张幻灯片。
1. 设置所需的尺寸。
1. 获取所需尺寸的缩略图。
1. 调用具有 BMP 输出参数的 Save() 方法。
1. 在兼容程序中打开 BMP 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有适用于 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境的兼容操作系统。
- 项目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="POT 到 BMP C++ 转换源代码" offSpacer="" %}}

```cs
// Load the POT
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.pot");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.bmp", ImageFormat::get_Bmp());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="免費應用程序將POT轉換為BMP" 
        sectionDescription="[嘗試我們的免費應用程序將PPT轉換為BMP](https://products.aspose.app/slides/conversion/ppt-to-bmp)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 POT 转换为许多其他文件格式，包括下面列出的一些文件格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-emf/" name="POT TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-gif/" name="POT TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-html/" name="POT TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-jpeg/" name="POT TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-pdf/" name="POT TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-png/" name="POT TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-potm/" name="POT TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-potx/" name="POT TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-pps/" name="POT TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-ppsm/" name="POT TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-ppsx/" name="POT TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-ppt/" name="POT TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-pptm/" name="POT TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-pptx/" name="POT TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-svg/" name="POT TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-tiff/" name="POT TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-xml/" name="POT TO XML" description="可扩展标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/pot-to-xps/" name="POT TO XPS" description="XML 纸张规格" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}