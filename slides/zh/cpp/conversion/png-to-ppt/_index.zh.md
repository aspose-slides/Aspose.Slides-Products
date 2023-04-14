---
title: 在 C++ 中将 PNG 转换为 PPT
url: /zh/cpp/conversion/png-to-ppt/
keywords: 将 PNG 转换为 PPT、将 PNG 转换为 PPT、PowerPoint、PNG、PPT、C++ API、C++ 库
description: 在 C++ 中将 PNG 转换为 PPT。使用 C++ 库 API 将 PNG 图像转换为 PowerPoint
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中将 PNG 转换为 PPT" h2="强大的跨平台 C++ API，用于使用 C++ 代码将 PNG 转换为 PPT" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 将 PNG 转换为 PPT" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 是一个功能强大的 C++ 库，用于创建、转换和操作 PowerPoint 演示文稿、PDF、HTML 文档和其他文件。将 PNG 转换为 PPT 时，实际上是在创建包含基于 PNG 图像的幻灯片的 PowerPoint 演示文稿。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="在 C++ 中将 PNG 转换为 PPT" %}}
使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/)，您只需几行代码就可以将 PNG 图像转换为 PowerPoint 演示文稿：

{{% blocks/products/pf/agp/code-block title="将PNG转PPT的C++代码" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C++ 中将 PNG 转换为 PPT" >}}


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
加载要转换为 PPT 的 PNG 图像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
将生成的文件另存为 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免费在线转换器" sectionDescription="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的 PowerPoint 转换" subTitle="您还可以将其他格式的文件转换为 PowerPoint" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}