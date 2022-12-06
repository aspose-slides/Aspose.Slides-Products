---
title: 在 C++ 中將圖像合併為 PDF
url: /zh-hant/cpp/merger/image-to-pdf/
keywords: 圖像到 PDF、合併圖像到 PDF、將圖像合併到 PDF、PDF、圖像、C++ API、C++ 庫
description: 在 C++ 中將圖像合併為 PDF。使用 C++ 庫 API 合併圖像和 PDF
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="在 C++ 中將圖像合併為 PDF" h2="用於使用 C++ 代碼將圖像合併為 PDF 文件的高速跨平台 C++ 庫" >}}

{{% blocks/products/pf/feature-page-section h2="使用 Aspose.Slides 將圖像合併為 PDF" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個功能強大的 C++ 庫，用於創建、轉換、合併和操作演示文稿、PDF、圖像和其他文件。當您將圖像合併為 PDF 時，您實際上是在組合圖像以獲得單個 PDF 文件。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="在 C++ 中將圖像合併為 PDF" %}}
使用 [**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/)，只需幾行代碼即可快速將圖像合併為 PDF

{{% blocks/products/pf/agp/code-block title="用於將圖像合併為 PDF 的 C++ 代碼" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

pres->Save(u"pres.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="如何在 C++ 中將圖像合併為 PDF" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
安裝**Aspose.Slides for C++**。請參閱 [**安裝**](https://docs.aspose.com/slides/cpp/installation/)。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
添加庫作為項目中的引用。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
創建一個 Presentation 類的實例。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
加載要合併為相框的圖像。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存生成的 PDF。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="合併其他文件" subTitle="您還可以合併其他格式的文件以獲得單個文件" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}