---
title: 使用 C++ 合併 PDF、PPT、PPTX 和許多其他文件格式
url: /zh-hant/cpp/merger/
keywords: 合併、加入、PowerPoint、演示文稿、C++、Aspose
description: 合併 C++ PPT、PPTX、ODP、PDF、PNG、JPG 等多個文件。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 中將 Powerpoint、PDF、PPT 或其他文檔合併在一起" h2="高速C++庫合併PPT、PPTX、PDF、PNG、JPEG等格式。" >}}

{{% blocks/products/pf/feature-page-section h2="使用 C++ 合併 PPT、PPTX、PDF" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/zh-hant/cpp/) 是一個強大的 C++ 庫，用於創建和操作演示文件。此外，它提供了靈活的方式來組合多個 PPT/PPTX 演示文稿。當您將一個演示文稿合併到另一個演示文稿時，您實際上是將他們的幻燈片合併到一個演示文稿中以獲得一個文件。 Aspose.Slides 允許您以不同的方式合併兩個演示文稿。您可以將演示文稿與其所有形狀、樣式、文本、格式、評論、動畫等合併，而不必擔心質量或數據丟失。

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 C++ 中合併 PowerPoint 演示文稿" %}}
要合併 PowerPoint 演示文稿，您需要將幻燈片從一個演示文稿克隆到另一個演示文稿。

{{% blocks/products/pf/agp/code-block title="使用 C++ 合併 PPTX 文件" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="使用 C++ 將演示文稿與幻燈片母版合併" %}}
此 C++ 代碼演示如何將多個演示文稿合併為一個並應用幻燈片母版演示模板中的樣式。因此，結果演示文稿將保持相同的源格式，並將包含來自另一個演示文稿的母版幻燈片的格式。

{{% blocks/products/pf/agp/code-block title="在 C++ 中將多個 PPT 合併為單個" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="如何使用 Aspose.Slides for C++ API 合併演示文稿" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="這些是合併兩個 PPTX 文件並將結果保存為 C++ 中的 PDF 的步驟。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
安裝 [**Aspose.Slides for C++**](https://docs.aspose.com/slides/cpp/installation/)。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
將庫引用（導入庫）添加到您的 C++ 項目。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
在 C++ 中打開源 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
使用 **AddClone** 方法合併 PPTX 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
保存演示文稿並將結果保存為單個 PDF 文件。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的合併格式" subTitle="您還可以組合其他文件格式。請參閱下面的其他支持的格式。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/zh-hant/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}