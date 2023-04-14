---
title: 在C++中將PPT轉換為Word
url: /zh-hant/cpp/conversion/ppt-to-word/
keywords: 將 PPT 轉換為 Word、PPT 轉換為 Word、PPT 轉換為 DOC、PowerPoint 轉換為 Word、C++ API、C++ 庫、CPP
description: 在 C++ 中將 PPT 轉換為 Word。使用 C++ 庫 API 將 PowerPoint 轉換為 Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在C++中將PPT轉換為Word" h2="強大的跨平台 C++ API，無需 Microsoft PowerPoint 或 Office 即可使用 C++ 代碼將 PowerPoint 轉換為 Word" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 和 Aspose.Words 將 PowerPoint 轉換為 Word" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 和 [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/) 是功能強大的 C++ 庫，用於操作和轉換 PowerPoint 演示文稿、Word 文檔和其他文件。將 PowerPoint 轉換為 Word 時，實際上是將演示文稿幻燈片的內容移動到 Word 文檔中的頁面。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C++ 中將 PowerPoint 轉換為 Word" %}}
幾行代碼即可快速將PPT轉Word

{{% blocks/products/pf/agp/code-block title="將 PowerPoint 轉換為 Word 的 C++ 代碼" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="如何將 PPT 轉換為 Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝 **Aspose.Slides for C++** 和 **Aspose.Words for C++** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建 Presentation 類和 Doc 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要轉換為 Word 的 PPT 演示文稿。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
根據幻燈片的內容生成圖像和文本。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 Word 文檔。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="免費在線轉換器" sectionDescription="[如何在 Python 中將 PPT 轉換為 HTML](https://products.aspose.com/slides/zh-hant/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 PowerPoint 轉換為其他格式的文件" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}