---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 使用 C# 查看 OTP
keywords: 查看 OTP, 打开 OTP, OTP 查看器, OTP, C# API, .NET 库
weight: 6830
url: /zh/net/viewer/otp/ 
description: 使用 C# 查看 OTP 文件。借助 Aspose.Slides for .NET 打开演示文稿文件并将其保存为 HTML。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="使用 C# 查看 OTP" h2="用于打开 OTP 文件并将其保存为响应式 HTML 的 C# API。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 查看 OTP" %}}

要查看 OTP 文件，请使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/)，这是一款功能丰富、强大且易于使用的 C# API。打开 [NuGet](https://www.nuget.org/packages/aspose.slides.net) 包管理器，搜索 **Aspose.Slides** 并安装。也可以在程序包管理器控制台中运行以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="程序包管理器控制台命令" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

借助 [**Aspose.Slides for .NET**](/slides/zh/net/)，只需几行代码即可加载 OTP 文件并将其保存为响应式 HTML。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用于查看 OTP 的 C# 代码" >}}
```cs
using var presentation = new Presentation("presentation.otp");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 C# 查看 OTP" intro="借助 Aspose.Slides，开发人员只需几行代码即可查看 OTP 文件。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 **Aspose.Slides for .NET**。请参阅[**安装**](https://docs.aspose.com/slides/net/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在项目中添加对该库的引用。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `Presentation` 类加载 `OTP` 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建 `ResponsiveHtmlController` 对象，用于输出响应式 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建 `HtmlOptions` 对象并设置 `HtmlFormatter` 属性。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 `SaveFormat.Html` 将 OTP 文件保存为 HTML。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="Aspose.Slides for .NET 支持所有主流操作系统。请确保满足以下先决条件。" %}}

- Microsoft Windows 或支持 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin 的兼容操作系统
- Microsoft Visual Studio 等开发环境
- 在项目中引用 Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="基于 Aspose.Slides 构建" title="在线查看 OTP 文件" description="免费的 Aspose.Slides Viewer 应用基于 [Aspose.Slides for .NET](https://products.aspose.com/slides/zh/net/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 OTP 文件。" button="打开 Aspose.Slides Viewer" note="[所有免费应用](https://products.aspose.app/slides/family)" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何呈现您的文件。
- 上传 OTP 文件并立即查看其幻灯片。
- 支持桌面和移动设备，无需 PowerPoint。
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="OTP" readMoreLink="https://docs.fileformat.com/presentation/otp/" %}}

Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. The contents of such a file include presentation information in the form of slides with text, images, shapes, multimedia content, transition effects and other slide elements. These template files are used for creating new presentations quickly based on the styling information stored in the template itself. OTP files can be created and saved with several different applications such as Impress that comes with OpenOffice suite and Microsoft PowerPoint. The OTP file format is similar to Microsoft PowerPoint template files .POT and .POTX.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="查看其他文件" subTitle="您还可以打开并查看其他格式的演示文稿。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/odp/" name="ODP" description="OpenDocument 演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/pot/" name="POT" description="PowerPoint 97-2003 模板" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/potm/" name="POTM" description="启用宏的 PowerPoint 模板" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/potx/" name="POTX" description="PowerPoint 模板" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/pps/" name="PPS" description="PowerPoint 97-2003 放映文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/ppsm/" name="PPSM" description="启用宏的 PowerPoint 放映文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/ppsx/" name="PPSX" description="PowerPoint 放映文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/pptm/" name="PPTM" description="启用宏的 PowerPoint 演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/net/viewer/pptx/" name="PPTX" description="PowerPoint 演示文稿" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
