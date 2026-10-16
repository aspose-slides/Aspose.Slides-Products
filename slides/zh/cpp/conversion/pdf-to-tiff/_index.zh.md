---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 C++ 中将 PDF 转换为 TIFF
url: /zh/cpp/conversion/pdf-to-tiff/
keywords: PDF 到 TIFF，将 PDF 转换为 TIFF，C++ API，C++ 库，PDF，TIFF
description: 在 C++ 中将 PDF 转换为 TIFF。使用 C++ 库 API 将 PDF 文件转换为 TIFF
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C++ 中将 PDF 转换为 TIFF" h2="高速和跨平台的 C++ 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 C++ 将 PDF 转换为 TIFF" variant="code" %}}

要将 PDF 转换为 TIFF，您需要从 PDF 文件创建演示文稿并将其另存为 TIFF。

{{< blocks/products/pf/slides-design-update-10-2026/code title="将 PDF 转换为 TIFF 的 C++ 代码" >}}
```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"InputPDF.pdf");
pres->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 C++ 中将 PDF 转换为 TIFF" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个强大的 C++ 库，用于创建和操作演示文稿文件。此外，它提供了将 PDF 转换为 TIFF 的灵活方法。使用**Aspose.Slides for C++**，任何开发人员或应用程序只需几行 C++ 代码即可将 PDF 转换为 TIFF 文件。

作为现代文档处理 API，Aspose.Slides for C++ 可以快速将 PDF 文件导出为 TIFF 文件格式。 Aspose PowerPoint 库允许您将 PDF 转换为 TIFF 和许多其他文件格式

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何使用 Aspose.Slides for C++ API 将 PDF 转换为 TIFF" intro="这些是在 C++ 中将 PDF 转换为 TIFF 的步骤。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库引用（导入库）添加到您的 C++ 项目。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}在 C++ 中打开源 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将结果保存为 TIFF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="免费在线转换器"
  description="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="将 PDF 转换为其他支持的格式" subTitle="您还可以转换 PDF 并保存为其他文件格式。查看下面所有支持的格式" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-html/" name="PDF TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-image/" name="PDF TO IMAGE" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-jpg/" name="PDF TO JPG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-png/" name="PDF TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-xml/" name="PDF TO XML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-svg/" name="PDF TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
