---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: 在 C++ 中编辑 PDF
url: /zh/cpp/editor/pdf/
keywords: 编辑 PDF、PDF、C++ API、C++ 库
description: 在 C++ 中编辑 PDF。使用 C++ 库 API 编辑 PDF 文档
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="在 C++ 中编辑 PDF" h2="用于使用 C++ 代码编辑 PDF 的高速跨平台 C++ 库" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="在 C++ 中编辑 PDF" variant="code" %}}

使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)，您只需几行代码即可向 PDF 文档添加新的文本行。

{{< blocks/products/pf/slides-design-update-10-2026/code title="用于编辑 PDF 的 C++ 代码" >}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromPdf(u"document.pdf");

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"document.pdf", SaveFormat::Pdf);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="使用 Aspose.Slides 编辑 PDF" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个功能强大的 C++ 库，用于操作和编辑演示文稿、PDF 文档和其他文件。您可以通过向其中添加新的文本行来编辑 PDF 文档。

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="如何在 C++ 中编辑 PDF" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}安装**Aspose.Slides for C++**。请参阅 [**安装**](https://docs.aspose.com/slides/cpp/installation/)。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}将库添加为项目中的参考。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}创建一个 Presentation 类的实例。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}加载要编辑的 PDF 文档。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}添加新的文本行。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}保存更改后的 PDF 文件。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="编辑其他文件" subTitle="您还可以编辑其他格式的文件" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/zh/cpp/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
