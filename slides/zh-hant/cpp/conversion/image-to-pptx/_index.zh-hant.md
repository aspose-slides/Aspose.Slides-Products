---
title: 在 C++ 中將圖像轉換為 PPTX
url: /zh-hant/cpp/conversion/image-to-pptx/
keywords: 圖像到 PPTX，將圖像轉換為 PPTX，C++ API，C++ 庫，圖像，PPTX
description: 在 C++ 中將圖像轉換為 PPTX。使用 C++ 庫 API 將圖像文件轉換為 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中將圖像轉換為 PPTX" h2="高速和跨平台的 C++ 庫，有助於開發能夠創建、合併、檢查或轉換 Microsoft PowerPoint 和 OpenOffice 演示文稿文件的應用程序，而無需使用 Microsoft 或 Open Office、Adobe PDF 等任何軟件。" >}}

{{% blocks/products/pf/feature-page-section h2="在 C++ 中將圖像轉換為 PPTX" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個強大的 C++ 庫，用於創建和操作演示文稿文件。此外，它還提供了將圖像轉換為 PPTX 的靈活方法。使用**Aspose.Slides for C++**，任何開發人員或應用程序只需幾行 C++ 代碼即可將圖像轉換為 PPTX 文件。

作為現代文檔處理API，Aspose.Slides for C++ 可快速將圖像文件導出為PPTX 文件格式。 Aspose PowerPoint 庫允許您將圖像轉換為 PDF 和許多其他文件格式

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 將圖像轉換為 PPTX" %}}
要將圖像轉換為 PPTX，您需要從圖像文件創建演示文稿並將其另存為 PPTX。

{{% blocks/products/pf/agp/code-block title="將圖像轉換為 PPTX 的 C++ 代碼" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);
pres->Save(u"presentation.pptx", SaveFormat::Pptx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for C++ API 將圖像轉換為 PPTX" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是在 C++ 中將圖像轉換為 PPTX 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 C++ 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 C++ 中打開源圖像文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將結果保存為 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="將圖像轉換為其他支持的格式" subTitle="您還可以轉換圖像並保存為其他文件格式。查看下面所有支持的格式" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/image-to-ppt/" name="IMAGE TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}