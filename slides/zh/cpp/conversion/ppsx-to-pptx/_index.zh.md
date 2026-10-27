---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 通过 C++ 应用程序将 PPSX 转换为 PPTX
weight: 8590
url: /zh/cpp/conversion/ppsx-to-pptx/ 
description: PPSX 文档到 PPTX 格式的示例 C++ 转换代码。使用示例代码在任何 C++ 应用程序中进行批量 PPSX 到 PPTX 的转换。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="通过 C++ 将 PPSX 转换为 PPTX" h2="使用 C++ 库进行高性能 PPSX 到 PPTX 转换，无需安装 Microsoft PowerPoint。"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="如何使用 C++ 将 PPSX 转换为 PPTX" %}}

为了将 PPSX 转换为 PPTX，我们将使用
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX 到 PPTX C++ 转换源代码" >}}
```cs
// Load the PPSX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.ppsx");
// Save in PPTX format.
prs->Save(u"convertedFile.pptx", Aspose::Slides::Export::SaveFormat::Pptx);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="通过 C++ 将 PPSX 转换为 PPTX 的步骤" intro="C++ 开发人员只需几行代码即可轻松地将 PPSX 文件转换为 PPTX。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}使用 Aspose.Slides 为 C++ 演示对象加载 PPSX 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}调用 Save() 方法。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}传递带有 (PPTX) 文件扩展名的输出文件路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX文件将保存在指定路径。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在兼容程序中打开PPTX文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="系统要求" intro="在运行 C++ 转换示例代码之前，请确保您具有以下先决条件。" %}}

- Microsoft Windows 或具有适用于 Windows 32 位、Windows 64 位和 Linux 64 位的 C++ 运行时环境的兼容操作系统。
- 项目中引用的 C++ DLL 的 Aspose.Slides。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="基于 Aspose.Slides 构建" title="在线将 PPSX 转换为 PPTX" description="免费的 Aspose.Slides Conversion 应用基于 [Aspose.Slides for C++](https://products.aspose.com/slides/zh/cpp/) 构建，与上方代码使用的是同一 API。打开它，看看 API 能如何处理您自己的 PPSX 文件。" button="打开 Aspose.Slides Conversion" note="[所有免费应用](https://products.aspose.app/slides/family)" upload="拖放或上传您的文件" saveAs="另存为" convert="转换" >}}
- 在浏览器中运行，无需安装任何软件。
- 在编写代码之前，先看看 Aspose.Slides 如何转换文件。
- 上传 PPSX 文件并将其另存为 PPTX。
- 下载结果或转换更多文件。
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="其他支持的转换" subTitle="您还可以将 PPSX 转换为许多其他文件格式，包括下面列出的几种文件格式。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="位图图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-emf/" name="PPSX TO EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="图形交换格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-html/" name="PPSX TO HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG图像" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument 演示格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument 标准格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-png/" name="PPSX TO PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="微软 PowerPoint 模板文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint 模板演示文稿" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="启用宏的幻灯片放映" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="微软PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-pptm/" name="PPSX TO PPTM" description="启用宏的演示文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-xml/" name="PPSX TO XML" description="可扩展标记语言" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML 纸张规格" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
