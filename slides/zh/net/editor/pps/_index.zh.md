---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 .NET 编辑 PPS 文件
url: /zh/net/editor/pps/ 
description: 用于在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上编辑 PPS 文档的 C# 源代码。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C# 中编辑 PPS 格式" h2="使用用于 .NET API 的服务器端 Aspose.Slides 进行本机和高性能 PPS 文档编辑，无需使用 Microsoft 或 Adob​​e PDF 等任何软件。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 编辑 PPS 文件" %}}

为了编辑 PPS 文件，我们将使用 <a href="https://products.aspose.com/slides/zh/net">Aspose.Slides for .NET</a> API，这是一个功能丰富、功能强大的 API以及适用于任何编辑器的 C# 平台的易于使用的 API。打开 <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> 包管理器，搜索 <b>Aspose.Slides</b> 并安装。您还可以从包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="编辑 PPS 文件 - C#" >}}
```cs
using var presentation = new Presentation("document.pps");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.pps", SaveFormat.Pps);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="在 C# 中编辑 PPS 文件的步骤" intro="一个基本的文档编辑 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net) 只需几行代码即可完成 API。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 对象加载 PPS 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}通过变量访问目标幻灯片和形状。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}通过 `TextFrame` 更新文本。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Pps` 保存编辑后的演示文稿。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="所有主要平台和操作系统都支持我们的 API。在执行以下代码之前，请确保您的系统具有以下先决条件。" %}}

- Microsoft Windows 或兼容 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台的操作系统
- Microsoft Visual Studio 等开发环境
- 项目中引用的 .NET DLL 的 Aspose.Slides - 使用上面的下载按钮从 NuGet 安装

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="基于 Aspose.Slides 构建" title="在线编辑 PPTX 文件" description="免费的 Aspose.Slides Editor 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTX 文件。" button="打开 Aspose.Slides Editor" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何处理您的文件。
- 上传 PPTX 文件并立即编辑。
- 保存并下载编辑后的文件。
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

扩展名为 PPS 的文件是 PowerPoint 97-2003 幻灯片放映文件。PPS 文件会直接以幻灯片放映的形式打开，并且可以包含幻灯片、文本、图表、图像、多媒体和格式。

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
