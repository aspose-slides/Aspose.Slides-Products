---
title: 在 C++ 中將 SVG 轉換為 PNG
url: /zh-hant/cpp/conversion/svg-to-png/
keywords: SVG 到 PNG，將 SVG 轉換為 PNG，C++ API，C++ 庫，SVG，PNG
description: 在 C++ 中將 SVG 轉換為 PNG。使用 C++ 庫 API 將 SVG 文件轉換為 PNG
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中將 SVG 轉換為 PNG" h2="高速和跨平台的 C++ 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 C++ 中將 SVG 轉換為 PNG" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個強大的 C++ 庫，用於創建和操作演示文稿文件。此外，它提供了將 SVG 轉換為 PNG 的靈活方法。使用**Aspose.Slides for C++**，任何開發人員或應用程序只需幾行 C++ 代碼即可將 SVG 轉換為 PNG 文件。

作為現代文檔處理 API，Aspose.Slides for C++ 可快速將 SVG 文件導出為 PNG 文件格式。 Aspose PowerPoint 庫允許您將 SVG 轉換為 PNG 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 將 SVG 轉換為 PNG" %}}
要將 SVG 轉換為 PNG，您需要從 SVG 文件創建演示文稿並將其另存為 PNG。

{{% blocks/products/pf/agp/code-block title="將 SVG 轉換為 PNG 的 C++ 代碼" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
System::String svgContent = System::IO::File::ReadAllText(svgPath);
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(svgContent);
System::SharedPtr<IPPImage> ppImage = pres->get_Images()->AddImage(svgImage);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(Aspose::Slides::ShapeType::Rectangle, 0.0f, 0.0f, 
    static_cast<float>(ppImage->get_Width()), 
    static_cast<float>(ppImage->get_Height()), ppImage);
for (int32_t i = 0; i < pres->get_Slides()->get_Count(); i++)
{
    // Control hidden slides (do not render hidden slides)
    if (pres->get_Slides()->idx_get(i)->get_Hidden())
    {
        continue;
    }
    
    // Convert slide to a Bitmap object
    System::SharedPtr<Bitmap> bmp = pres->get_Slides()->idx_get(i)->GetThumbnail(2.f, 2.f);

    // Create file name for an image
    System::String outputFilePath = Path::Combine(outputDir, System::String(u"Slide_") + i + u".png");
    
    // Save the image in PNG format
    bmp->Save(outputFilePath, ImageFormat::get_Png());
}

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for C++ API 將 SVG 轉換為 PNG" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 C++ 中將 SVG 轉換為 PNG 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 C++ 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 C++ 中打開源 SVG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PNG 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將 SVG 轉換為其他支持的格式" subTitle="您還可以轉換 SVG 並保存為其他文件格式。查看下面所有支持的格式" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}