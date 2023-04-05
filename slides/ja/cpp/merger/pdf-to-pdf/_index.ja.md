---
title: C++ で PDF ファイルをマージする
url: /ja/cpp/merger/pdf-to-pdf/
keywords: PDF のマージ、PDF から PDF、PDF の結合、PDF の結合、C++ API、C++ ライブラリ
description: C++ で PDF を PDF にマージします。 C++ ライブラリ API を使用して PDF ファイルを結合する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で PDF をマージする" h2="C++ コードを使用して PDF ファイルをマージするための高速でクロスプラットフォームの C++ ライブラリ" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して PDF を PDF にマージ" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、プレゼンテーション、PDF、およびその他のドキュメントの作成、変換、マージ、および操作に使用される強力な C++ ライブラリです。 PDF を PDF にマージすると、2 つのドキュメントのページが効果的に結合され、1 つの PDF ファイルが得られます。 Aspose.Slides では、さまざまな方法で PDF をマージできます。 PDF をすべての形状、スタイル、テキスト、フォーマットなどと結合できます。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++ で PDF を PDF に結合" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) を使用すると、わずか数行のコードで PDF ファイルをすばやくマージできます。

{{% blocks/products/pf/agp/code-block title="PDF を PDF にマージするための C++ コード" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();
pres->get_Slides()->RemoveAt(0);

pres->get_Slides()->AddFromPdf(u"InputPDF1.pdf");
pres->get_Slides()->AddFromPdf(u"InputPDF2.pdf");

pres->Save(u"pres.pdf", SaveFormat::Pdf);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++ で PDF をマージする方法" >}}


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
結合する PDF ファイルを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の PDF を保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="merger" extension="" sectionTitle="PDFファイルをオンラインで結合" sectionDescription="[Python で PDF をマージする方法](https://products.aspose.com/slides/ja/python-net/merge/pdf/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="他のファイルをマージする" subTitle="他の形式のファイルを結合して 1 つのファイルにすることもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}