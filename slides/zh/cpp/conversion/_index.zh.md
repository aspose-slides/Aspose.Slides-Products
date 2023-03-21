---
title: 使用 C++ 将 Microsoft PowerPoint 演示文稿转换为各种格式
url: /zh/cpp/conversion/
description: 在基于 C++ 的应用程序中将 Microsoft PowerPoint 幻灯片转换为多个文件，包括 HTML、PDF 和图像格式。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> 通过 C++ 转换 PowerPoint 演示文稿" h2="用于不同转换场景的C++示例代码，将幻灯片转换为图像、HTML、PDF等格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Microsoft<sup>®</sup> PowerPoint 格式的转换过程简单且易于使用 C++ PowerPoint 库自动化过程。开发人员可以增强相关源代码并将其集成到他们的应用程序中。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 格式的相互转换" %}}
Microsoft<sup>®</sup> PowerPoint 文档（包括 PPT、PPTX）以编程方式相互转换只是两行代码。使用 [Presentation 类](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) 加载文件并调用 [Save 方法](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) 具有输出文件和 SaveFormat.OutputFormats 作为参数。

{{% blocks/products/pf/feature-page-code h3="C++ 转换代码" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="将 PowerPoint 文件转换为 PDF" %}}

由于 PDF 文档的大量共享，将 Microsoft<sup>®</sup> PowerPoint 转换为 PDF 是一种常见情况。程序员可以使用 [PdfOptions 类](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) 将其自动化并设置相关的 PDF 转换设置。一些具体设置，例如文本压缩级别、JPEG 质量 [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861)、PDF 合规级别 [Compliance](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f)，转换隐藏幻灯片[ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23），选定的幻灯片并生成锁定的[密码]（https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7）受保护的PDF文件.

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint 到 PDF 转换代码" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="将 Microsoft PowerPoint 幻灯片另存为图像" %}}
每当需要在 Web 上显示演示内容时，就需要将文件呈现为 HTML 或图像 JPG、TIFF、PNG 等。将幻灯片转换为图像的过程很简单。使用 [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) 获取所有幻灯片并一张一张地遍历每张幻灯片。在每次迭代期间，对幻灯片图像使用 [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783)，然后保存为所需的图像格式。 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint 到图像转换" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}