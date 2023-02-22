---
title: 在 C++ 中将图像转换为 PPTX
url: /zh/cpp/conversion/image-to-pptx/
keywords: 图像到 PPTX，将图像转换为 PPTX，C++ API，C++ 库，图像，PPTX
description: 在 C++ 中将图像转换为 PPTX。使用 C++ 库 API 将图像文件转换为 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中将图像转换为 PPTX" h2="高速和跨平台的 C++ 库，有助于开发能够创建、合并、检查或转换 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的应用程序，而无需使用 Microsoft 或 Open Office、Adobe PDF 等任何软件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 C++ 中将图像转换为 PPTX" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个强大的 C++ 库，用于创建和操作演示文稿文件。此外，它还提供了将图像转换为 PPTX 的灵活方法。使用**Aspose.Slides for C++**，任何开发人员或应用程序只需几行 C++ 代码即可将图像转换为 PPTX 文件。

作为现代文档处理API，Aspose.Slides for C++ 可快速将图像文件导出为PPTX 文件格式。 Aspose PowerPoint 库允许您将图像转换为 PDF 和许多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 将图像转换为 PPTX" %}}
要将图像转换为 PPTX，您需要从图像文件创建演示文稿并将其另存为 PPTX。

{{% blocks/products/pf/agp/code-block title="将图像转换为 PPTX 的 C++ 代码" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.pptx", SaveFormat::Pptx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for C++ API 将图像转换为 PPTX" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="这些是在 C++ 中将图像转换为 PPTX 的步骤。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安装 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将库引用（导入库）添加到您的 C++ 项目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 C++ 中打开源图像文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将结果保存为 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="将图像转换为其他支持的格式" subTitle="您还可以转换图像并保存为其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}