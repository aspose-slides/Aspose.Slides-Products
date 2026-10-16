---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 C++ 应用程序将 XML 转换为 PDF
weight: 620
url: /zh/cpp/conversion/xml-to-pdf/ 
description: XML 文档到 PDF 格式的示例 C++ 转换代码。在任何 C++ 应用程序中使用示例代码将 XML 批量转换为 PDF。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通过 C++ 将 XML 转换为 PDF" h2="使用 C++ 库进行高性能 XML 到 PDF 转换，无需安装 Microsoft PowerPoint。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C++ 将 XML 转换为 PDF" %}}

为了将 XML 转换为 PDF，我们将使用
 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/)
 API 是一个功能丰富、功能强大且易于使用的 C++ 平台文档操作和转换 API。可以直接下载最新版本，直接打开
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 包管理器，搜索
 Aspose.Slides.Cpp
 并安装。您也可以从包管理器控制台使用以下命令。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="命令" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="XML 到 PDF C++ 转换源代码" >}}
```cs
// Load the XML.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.xml");
// Save in PDF format.
prs->Save(u"convertedFile.pdf", Aspose::Slides::Export::SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通过 C++ 将 XML 转换为 PDF 的步骤" intro="C++ 开发人员只需几行代码即可轻松地将 XML 文件转换为 PDF。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Aspose.Slides 为 C++ 演示对象加载 XML 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 Save() 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}传递带有 (PDF) 文件扩展名的输出文件路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF文件将保存在指定路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在兼容程序中打开 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。" %}}

- Microsoft Windows 或具有适用于 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境的兼容操作系统。
- 项目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免費應用程序將XML轉換為PDF"
  description="[嘗試我們的免費Editor app](https://products.aspose.app/slides/editor/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 XML 转换为许多其他文件格式，包括下面列出的几种。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-bmp/" name="XML TO BMP" description="位图图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-emf/" name="XML TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-gif/" name="XML TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-html/" name="XML TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-jpeg/" name="XML TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-odp/" name="XML TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-otp/" name="XML TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-png/" name="XML TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-pot/" name="XML TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-potm/" name="XML TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-potx/" name="XML TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-pps/" name="XML TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-ppsm/" name="XML TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-ppsx/" name="XML TO PPSX" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-ppt/" name="XML TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-pptm/" name="XML TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-pptx/" name="XML TO PPTX" description="打开 XML 表示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-svg/" name="XML TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-tiff/" name="XML TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/xml-to-xps/" name="XML TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
