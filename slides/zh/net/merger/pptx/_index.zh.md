---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 .NET 合并 PPTX 文件
weight: 3150
url: /zh/net/merger/pptx/ 
description: 用于在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上组合 PPTX 文档的 C# 源代码。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C# 中合并 PPTX 格式" h2="使用用于 .NET API 的服务器端 Aspose.Slides 进行本机和高性能 PPTX 文档合并，无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 合并 PPTX 文件" %}}

为了合并 PPTX 文件，我们将使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net)
 API 是一个功能丰富、功能强大且易于使用的 C# 平台文档操作和合并 API。打开
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 **Aspose.Slides**
 并安装。您还可以从包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="合并 PPTX 文件 - C#" >}}
```cs
var ps1 = new Presentation("presen1.pptx");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPTX presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="在 C# 中合并 PPTX 文件的步骤" intro="只需几行代码即可完成与 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net) API 合并和连接的基本文档。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用完整路径加载所有 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}制作一份文件作为基础文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用相关方法一一拼接合并文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 Save() 方法并将文件名（完整路径）和格式（PPTX）作为参数传递。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}现在您可以在 Microsoft Office、Adobe PDF 或任何其他兼容程序中打开和使用 PPTX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="所有主要平台和操作系统都支持我们的 API。在执行以下代码之前，请确保您的系统具有以下先决条件。" %}}

- Microsoft Windows 或兼容 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的操作系统
- Microsoft Visual Studio 等开发环境
- 项目中引用的 .NET DLL 的 Aspose.Slides - 使用上面的下载按钮从 NuGet 安装

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="在线合并 PDF 文件"
  description="[如何在 Python 中合并 PDF](https://products.aspose.com/slides/zh/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTX" readMoreLink="https://docs.fileformat.com/presentation/pptx/" %}}

扩展名为 `.PPTX` 的文件使用随 PowerPoint 2007 推出的 PowerPoint Open XML 演示文稿格式。与较旧的二进制 PPT 格式不同，PPTX 将演示文稿数据存储在 Office Open XML 包中。PPTX 文件包含一组幻灯片，可包括文本、图像、格式、动画和其他媒体，以及演示文稿设置。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的合并格式" subTitle="使用 C#，One 还可以合并许多其他文件格式，包括。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/odp/" name="ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/otp/" name="OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/pot/" name="POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/potm/" name="POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/potx/" name="POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/pps/" name="PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/ppsm/" name="PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/ppsx/" name="PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/ppt/" name="PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/merger/pptm/" name="PPTM" description="启用宏的演示文件" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
