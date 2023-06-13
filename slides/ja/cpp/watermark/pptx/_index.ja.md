---
title: C++ を使用して、PPTX プレゼンテーション ファイルにウォーターマークを追加します
url: /ja/cpp/watermark/pptx/
keywords: ウォーターマークの追加 PPTX、テキストのウォーターマークの追加 PPTX、画像のウォーターマークの追加 PPTX
description: PPTX プレゼンテーションにウォーターマークを追加するための C++ ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ を使用して PPTX プレゼンテーションにウォーターマークを追加します" h2="独自の C++ アプリを構築し、サーバー側 API を使用してテキストまたは画像の透かしを PPT、PPTX、または ODP プレゼンテーションに挿入します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ 経由で PPTX プレゼンテーションにウォーターマークを追加します" %}}
Aspose.Slides for C++ を使用すると、PPTX プレゼンテーションにウォーターマークを追加できます。ウォーターマークはプレゼンテーションに不可欠な部分です。これらは、プレゼンテーションのコンテンツが許可なくコピーまたは使用されないように保護するために使用されます。ウォーターマークは、プレゼンテーションの上に配置される、表示または非表示の画像またはテキストです。プレゼンテーションの所有者を特定し、不正使用を防ぐために使用できます。透かしを使用すると、プレゼンテーションにプロフェッショナルな雰囲気を加え、より洗練された外観にすることもできます。 
{{% blocks/products/pf/agp/code-block title="C++ を使用してテキスト透かしを PPTX に追加します" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermark.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C++ を使用して画像ウォーターマークを PPTX プレゼンテーションに追加します" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto master = presentation->get_Masters()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 0.0f, 0.0f);

auto image = presentation->get_Images()->AddImage(:File::ReadAllBytes(u"watermark.png"));

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(image);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"watermark2.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ 経由で PPTX にウォーターマークを追加する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPTX ファイルにテキストの透かしを追加する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPTX を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
マスタープレゼンテーションを選択してください
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddAutoShape メソッドを使用して形状タイプを追加する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
AddTextFrame メソッドを使用して透かしテキストを追加する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPTX 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている形式" subTitle="C++ を使用すると、次の形式にウォーターマークを追加することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/watermark/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}