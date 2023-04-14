---
title: C++ で JPG を PPT に変換する
url: /ja/cpp/conversion/jpg-to-ppt/
keywords: JPG を PPT に、JPG を PPT に、PowerPoint に、JPG に、PPT に、C++ API に、C++ ライブラリに変換する
description: C++ で JPG を PPT に変換します。 C++ ライブラリ API を使用して JPG 画像を PowerPoint に変換する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で JPG を PPT に変換する" h2="C++ コードを使用して JPG を PPT に変換するための強力なクロスプラットフォーム C++ API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して JPG を PPT に変換する" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、PowerPoint プレゼンテーション、PDF、HTML ドキュメントなどの作成、変換、操作に使用される強力な C++ ライブラリです。ファイル。 JPG を PPT に変換すると、基本的に JPG 画像に基づくスライドを含む PowerPoint プレゼンテーションが作成されます。

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="C++ で JPG を PPT に変換する" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) を使用すると、わずか数行のコードで JPG 画像を PowerPoint プレゼンテーションに変換できます。

{{% blocks/products/pf/agp/code-block title="JPG を PPT に変換するための C++ コード" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.jpg"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++ で JPG を PPT に変換する方法" >}}


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
PPT に変換する JPG 画像を読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果のファイルを PPT プレゼンテーションとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他の PowerPoint 変換" subTitle="他の形式のファイルを PowerPoint に変換することもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}