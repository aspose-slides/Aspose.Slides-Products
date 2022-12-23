---
title: C++ で HTML を編集する
url: /ja/cpp/editor/html/
keywords: HTML、HTML、C++ API、C++ ライブラリの編集
description: C++ で HTML を編集します。 C++ ライブラリ API を使用して HTML ファイルを編集する
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ で HTML を編集する" h2="C++ コードを使用して HTML を編集するための高速でクロスプラットフォームの C++ ライブラリ" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides を使用して HTML を編集する" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) は、プレゼンテーション、HTML ドキュメント、およびその他のファイルの操作と編集に使用される強力な C++ ライブラリです。新しいテキスト行を追加することで、HTML ドキュメントを編集できます。 

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="C++ で HTML を編集する" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/ja/cpp/) を使用すると、わずか数行のコードで HTML ドキュメントに新しいテキスト行を追加できます。

{{% blocks/products/pf/agp/code-block title="HTML を編集するための C++ コード" offSpacer="true" %}}
```cpp

auto pres = System::MakeObject<Presentation>();

pres->get_Slides()->RemoveAt(0);
pres->get_Slides()->AddFromHtml(htmlText1);

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 50.0f);
shape->get_TextFrame()->set_Text(u"New text");

pres->Save(u"page.html", SaveFormat::Html5);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C++ で HTML を編集する方法" >}}


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
編集する HTML ドキュメントを読み込みます。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
新しいテキスト行を追加します。
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
変更した HTML ファイルを保存します。
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="他のファイルを編集する" subTitle="他の形式のファイルを編集することもできます" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/cpp/editor/pdf/" name="Edit PDF" >}}  



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}