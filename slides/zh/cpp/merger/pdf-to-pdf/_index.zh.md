---
title: 在 C++ 中合并 PDF 文件
url: /zh/cpp/merger/pdf-to-pdf/
keywords: 合并 PDF、PDF 到 PDF、合并 PDF、合并 PDF、C++ API、C++ 库
description: 在 C++ 中将 PDF 合并为 PDF。使用C++库API合并PDF文件
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中合并 PDF" h2="用于使用 C++ 代码合并 PDF 文件的高速跨平台 C++ 库" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 将 PDF 合并为 PDF" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个功能强大的 C++ 库，用于创建、转换、合并和操作演示文稿、PDF 和其他文档。将 PDF 合并为 PDF 时，实际上是将 2 个文档的页面合并为一个 PDF 文件。 Aspose.Slides 允许您以不同的方式合并 PDF。您可以合并 PDF 及其所有形状、样式、文本、格式等。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C++ 中将 PDF 合并为 PDF" %}}
使用[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)，只需几行代码即可快速合并PDF文件

{{% blocks/products/pf/agp/code-block title="将 PDF 合并为 PDF 的 C++ 代码" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->RemoveAt(0);

pres->get_Slides()->AddFromPdf(u"InputPDF1.pdf");
pres->get_Slides()->AddFromPdf(u"InputPDF2.pdf");

pres->Save(u"pres.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C++ 中合并 PDF" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安装**Aspose.Slides for C++**。请参阅 [**安装**](https://docs.aspose.com/slides/cpp/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库添加为项目中的参考。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建一个 Presentation 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要合并的 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 PDF。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="合并其他文件" subTitle="您还可以合并其他格式的文件以获取单个文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}