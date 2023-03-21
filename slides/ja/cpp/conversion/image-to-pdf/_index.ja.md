---
title: C++ で Image を PDF に変換する
url: /ja/cpp/conversion/image-to-pdf/
keywords: Image から PDF へ、Image から PDF への変換、C++ API、C++ ライブラリ、Image、PDF
description: C++ で Image を PDF に変換します。 C++ ライブラリ API を使用して Image ファイルを PDF ファイルに変換します
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で Image を PDF に変換する" h2="MicrosoftやOpen Office、Adobe PDFなどのソフトウェアを使用せずに、Microsoft PowerPointおよびOpenOfficeプレゼンテーションファイルを作成、マージ、検査、または変換する機能を備えたアプリケーションの開発に役立つ、高速でクロスプラットフォームのC++ライブラリ。" >}}

{{% blocks/products/pf/feature-page-section h2="C++ で Image を PDF に変換する" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、プレゼンテーション ファイルを作成および操作するための強力な C++ ライブラリです。さらに、Image を PDF に柔軟に変換する方法を提供します。 **Aspose.Slides for C++** を使用すると、開発者やアプリケーションは、わずか数行の C++ コードで Image ファイルを PDF ファイルに変換できます。

最新のドキュメント処理 API である Aspose.Slides for C++ は、Image ファイルを PDF ファイル フォーマットにすばやくエクスポートします。 Aspose PowerPoint ライブラリを使用すると、Image を PDF やその他の多くのファイル形式に変換できます

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ を使用して Image を PDF に変換します" %}}
Image を PDF に変換するには、Image ファイルからプレゼンテーションを作成し、PDF として保存する必要があります。

{{% blocks/products/pf/agp/code-block title="Image を PDF に変換する C++ コード" offSpacer="true" %}}

```cpp

auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pdf", SaveFormat::Pdf);

```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API を使用して Image を PDF に変換する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、C++ で Image を PDF に変換する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) をインストールします。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++ プロジェクトにライブラリ参照を追加 (ライブラリをインポート) します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ソース Image ファイルを C++ で開きます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PDF ファイルとして保存します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Image を他のサポートされている形式に変換する" subTitle="Image を変換して、他のファイル形式に保存することもできます。以下のサポートされているすべての形式を参照してください" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/image-to-jpg/" name="IMAGE TO JPG" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}