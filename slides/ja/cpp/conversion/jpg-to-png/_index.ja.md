---
title: C++ で JPG を PNG に変換する
url: /ja/cpp/conversion/jpg-to-png/
keywords: JPG から PNG へ、JPG から PNG への変換、C++ API、C++ ライブラリ、JPG、PNG
description: C++ で JPG を PNG に変換します。 C++ ライブラリ API を使用して JPG ファイルを PNG ファイルに変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で JPG を PNG に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのC++ライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="C++ で JPG を PNG に変換する" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、プレゼンテーション ファイルを作成および操作するための強力な C++ ライブラリです。さらに、JPG を PNG に柔軟に変換する方法を提供します。 **Aspose.Slides for C++** を使用すると、開発者やアプリケーションは、わずか数行の C++ コードで JPG ファイルを PNG ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for C++ は、JPG ファイルを PNG ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、JPG を PNG やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ を使用して JPG を PNG に変換します" %}}
JPG を PNG に変換するには、JPG ファイルからプレゼンテーションを作成し、PNG として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="JPG を PNG に変換する C++ コード" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
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

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API を使用して JPG を PNG に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、C++ で JPG を PNG に変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++ プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース JPG ファイルを C++ で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PNG ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="JPG を他のサポートされている形式に変換する" subTitle="JPG を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/jpg-to-image/" name="JPG TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/jpg-to-pdf/" name="JPG TO PDF" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}