---
title: C++ で PPT を Word に変換する
url: /ja/cpp/conversion/ppt-to-word/
keywords: PPT を Word に、PPT を Word に、PPT を DOC に、PowerPoint を Word に、C++ API、C++ ライブラリ、CPP に変換
description: PPT を C++ の Word に変換します。 C++ ライブラリ API を使用して PowerPoint を Word に変換する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で PPT を Word に変換する" h2="Microsoft PowerPoint や Office を使用せずに C++ コードを使用して PowerPoint を Word に変換するための強力なクロスプラットフォーム C++ API" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides と Aspose.Words を使用して PowerPoint を Word に変換" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) および [**Aspose.Words for C++**](https://products.aspose.com/ words/cpp/) は、PowerPoint プレゼンテーション、Word ドキュメント、およびその他のファイルの操作と変換に使用される強力な C++ ライブラリです。 PowerPoint を Word に変換すると、基本的にプレゼンテーションのスライドの内容が Word 文書のページに移動されます。

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++ で PowerPoint を Word に変換する" %}}
わずか数行のコードで PPT を Word にすばやく変換できます

{{% blocks/products/pf/agp/code-block title="PowerPoint を Word に変換するための C++ コード" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPT を Word に変換する方法" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** と **Aspose.Words for C++** をインストールします。 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation クラスと Doc クラスのインスタンスを作成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word に変換する PPT プレゼンテーションを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
スライドの内容に基づいて画像とテキストを生成します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果の Word ドキュメントを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="無料のオンラインコンバーター" sectionDescription="[Python で PPT を HTML に変換する方法](https://products.aspose.com/slides/ja/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="PowerPoint を他の形式のファイルに変換することもできます" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}