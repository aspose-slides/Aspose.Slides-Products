---
title: C++ で画像を BMP にマージ
url: /ja/cpp/merger/image-to-bmp/
keywords: BMP への画像、BMP への画像の結合、BMP への画像の結合、画像の結合、画像、BMP、C++ API、C++ ライブラリ
description: C++ でイメージを BMP にマージします。 C++ ライブラリ API を使用して画像を結合する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で画像を BMP にマージ" h2="C++ コードを使用してイメージを BMP ファイルにマージするための高速でクロスプラットフォームの C++ ライブラリ" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して画像を BMP にマージ" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、プレゼンテーション、PDF、画像などの作成、変換、マージ、操作に使用される強力な C++ ライブラリです。ファイル。画像を BMP にマージすると、効果的に画像を組み合わせて 1 つの BMP ファイルを取得します。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++ で画像を BMP にマージ" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) を使用すると、わずか数行のコードで画像を BMP にすばやくマージできます。

{{% blocks/products/pf/agp/code-block title="Image を BMP にマージするための C++ コード" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
        
auto image1 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image1.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 100.0f, 100.0f, image1);
auto image2 = pres->get_Images()->AddImage(File::ReadAllBytes(u"image2.png"));
pres->get_Slides()->idx_get(0)->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 200.0f, 100.0f, 100.0f, image2);

for (int32_t index = 0; index < pres->get_Slides()->get_Count(); index++)
{
    auto slide = pres->get_Slides()->idx_get(index);
    auto fileName = String::Format(u"slide_{0}.bmp", index);
    slide->GetThumbnail()->Save(fileName, ImageFormat::get_Bmp());
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++ で画像を BMP にマージする方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** をインストールします。 [**インストール**](https://docs.aspose.com/slides/cpp/installation/) を参照してください。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ライブラリを参照としてプロジェクトに追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーション クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結合する画像をピクチャ フレームとして読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の BMP ファイルを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="他のファイルをマージする" subTitle="他の形式のファイルを結合して 1 つのファイルにすることもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/jpg-to-jpg/" name="JPG TO JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/pdf-to-pdf/" name="PDF TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}