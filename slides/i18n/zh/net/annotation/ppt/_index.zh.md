---
title: 通过 .NET 删除 PPT 注释
weight: 4380
url: /zh/net/annotation/ppt/ 
description: 用于删除 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上的 PPT 格式注释的 C# 源代码。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 从 PPT 中删除评论和评论作者" h2="构建您自己的 .NET 应用程序，以使用服务器端 API 处理文档文件中的评论和作者。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 注释 PPT 文件" %}}

 为了注释 PPT 文件，我们将使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API 是一个功能丰富、功能强大且易于使用的 C# 平台文档操作 API。打开
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 **Aspose.Slides**
 并安装。您还可以从包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="通过 C# 从 PPT 中删除评论" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="您需要 [aspose.slides.dll](https://downloads.aspose.com/slides/net) 在您的环境中尝试代码。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 Presentation 类的实例加载 PPT
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
遍历加载的PPT的所有作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
循环并检查每个作者的所有评论
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
删除作者的所有评论
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
最后删除作者
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系统都支持 Aspose.Slides for .NET。只需确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系统。
- Microsoft Visual Studio 等开发环境。
- 项目中引用的 .NET DLL 的 Aspose.Slides。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="从 PPT 中删除注释 - C#" offSpacer="" %}}

```cs
// load PPT with a new instance of Presentation class
var presentation = new Aspose.Slides.Presentation("template.odp");
// iterate over comment authors
foreach (var author in presentation.CommentAuthors)
{
    // iterate over author comments
    foreach (var comment in author.Comments)
    {
        // remove comments
        author.Comments.Remove(comment);
    }
    // remove author
    author.Remove();
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Aspose.Slides for .NET API" %}}

 Aspose.Slides API 可用于读取、编写、操作 Microsoft PowerPoint 文档并将其转换为 PDF、XPS、HTML、TIFF、ODP 和各种其他格式。可以从头开始创建新文件并将其保存为相关支持的格式。 Aspose.Slides 是一个独立的 API，用于创建、解析或操作演示文稿、幻灯片和元素，它不依赖于 Microsoft 或 OpenOffice 等任何软件。  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remove Annotation from PPT via Online App" sectionDescription="Delete PPT document annotations right now by visiting our [Live Demos website](https://products.aspose.app/slides/annotation). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPT file and hit the \"Remove\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. A PPT file can contain several different types of information such as text, bulleted points, images, multimedia and other embedded OLE objects. Microsoft came up with newer file format for PowerPoint, known as PPTX, from 2007 onwards that is based on Office OpenXML and is different from this binary file format. Several other application programs such as OpenOffice Impress and Apple Keynote can also create PPT files.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的注释格式" subTitle="使用 C#，可以轻松地注释其他格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/annotation/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/annotation/pptx/" name="PPTX" description="打开 XML 表示格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}