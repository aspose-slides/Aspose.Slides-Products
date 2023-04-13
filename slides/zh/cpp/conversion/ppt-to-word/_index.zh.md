---
title: 在C++中将PPT转换为Word
url: /zh/cpp/conversion/ppt-to-word/
keywords: 将 PPT 转换为 Word、PPT 转换为 Word、PPT 转换为 DOC、PowerPoint 转换为 Word、C++ API、C++ 库、CPP
description: 在 C++ 中将 PPT 转换为 Word。使用 C++ 库 API 将 PowerPoint 转换为 Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在C++中将PPT转换为Word" h2="强大的跨平台 C++ API，无需 Microsoft PowerPoint 或 Office 即可使用 C++ 代码将 PowerPoint 转换为 Word" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 和 Aspose.Words 将 PowerPoint 转换为 Word" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh/cpp/) 和 [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/) 是功能强大的 C++ 库，用于操作和转换 PowerPoint 演示文稿、Word 文档和其他文件。将 PowerPoint 转换为 Word 时，实际上是将演示文稿幻灯片的内容移动到 Word 文档中的页面。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C++ 中将 PowerPoint 转换为 Word" %}}
几行代码即可快速将PPT转Word

{{% blocks/products/pf/agp/code-block title="将 PowerPoint 转换为 Word 的 C++ 代码" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何将 PPT 转换为 Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安装 **Aspose.Slides for C++** 和 **Aspose.Words for C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
创建 Presentation 类和 Doc 类的实例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加载要转换为 Word 的 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
根据幻灯片的内容生成图像和文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 Word 文档。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免费在线转换器" sectionDescription="[如何在 Python 中将 PPT 转换为 HTML](https://products.aspose.com/slides/zh/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 PowerPoint 转换为其他格式的文件" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}