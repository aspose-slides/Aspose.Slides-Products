---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 C# 将 PPTM 转换为 JPEG
weight: 7860
url: /zh/net/conversion/pptm-to-jpeg/ 
description: PPTM 到 JPEG C# 转换的示例代码。使用 API 示例代码在 VB.NET、Asp.NET 或任何基于 .NET 的应用程序中将批处理 PPTM 文件转换为 JPEG。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通过 C# 将 PPTM 转换为 JPEG" h2="在 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台上将 PowerPoint® PPTM 文件导出为 JPEG"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C# 将 PTM 转换为 JPEG" %}}

为了将 PPTM 转换为 JPEG，我们将使用
 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net)
 API 是一个功能丰富、功能强大且易于使用的 C# 平台文档操作和转换 API。打开
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 包管理器，搜索
 Aspose.Slides
 并安装。您还可以从包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="包管理器控制台命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="此示例代码显示 PPTM 到 JPEG C# 的转换" >}}
```cs
using (var presentation = new Presentation("template.pptm"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通过 C# 将 PPTM 转换为 JPEG 的步骤" intro=".NET 开发人员只需几行代码即可轻松加载 PPTM 文件并将其转换为 JPEG。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Presentation 类的实例加载 PPTM 文件{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}遍历演示文稿中的每张幻灯片{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}每次迭代都将全尺寸图像创建为位图{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 JPEG 文件扩展名和 ImageFormat.Jpeg 作为参数调用 Bitmap.Save 方法{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 .NET 转换示例源代码之前，请确保您具有以下先决条件。" %}}

- Microsoft Windows 或与 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 平台兼容的操作系统。
- Microsoft Visual Studio 等开发环境。
- 项目中引用的 .NET DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="基于 Aspose.Slides 构建" title="在线将 PPTM 转换为 JPEG" description="免费的 Aspose.Slides Conversion 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPTM 文件。" button="打开 Aspose.Slides Conversion" note="[所有免费应用](https://products.aspose.app/slides/family)" upload="拖放或上传您的文件" saveAs="另存为" convert="转换" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何转换文件。
- 上传 PPTM 文件并将其另存为 JPEG。
- 下载结果或转换更多文件。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PPTM 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="位图图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-emf/" name="PPTM TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-gif/" name="PPTM TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-html/" name="PPTM TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-png/" name="PPTM TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-potm/" name="PPTM TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-pps/" name="PPTM TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-pptx/" name="PPTM TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-svg/" name="PPTM TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF 格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
