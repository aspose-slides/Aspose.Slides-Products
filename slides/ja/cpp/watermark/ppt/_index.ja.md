---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPT プレゼンテーションに透かしを追加
url: /ja/cpp/watermark/ppt/
description: C++ で PPT プレゼンテーションにテキストまたは画像の透かしを追加します。Aspose.Slides for C++ を使用して、スライドに透かしを配置します。
keywords: PPT に透かしを追加, PPT にテキストの透かしを追加, PPT に画像の透かしを追加
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPT プレゼンテーションに透かしを追加する" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション ファイルにテキストまたは画像の透かしを追加できます。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ による PPT プレゼンテーションへの透かしの追加" variant="code" %}}

Aspose.Slides for C++ を使用すると、PPT プレゼンテーションにテキストまたは画像の透かしを追加できます。`AddAutoShape` でスライド マスターに透かしの図形を追加し、`AddTextFrame` でテキストを追加するか、`File::ReadAllBytes` と `AddImage` で読み込んだ画像で図形を塗りつぶします。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPT にテキストの透かしを追加" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 80);

watermarkShape->AddTextFrame(u"Watermark");
presentation->Save(u"watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPT プレゼンテーションに画像の透かしを追加" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");
auto masterSlide = presentation->get_Master(0);
auto watermarkShape = masterSlide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100, 100, 400, 200);

auto imageData = File::ReadAllBytes(u"watermark.png");
auto watermarkImage = presentation->get_Images()->AddImage(imageData);

watermarkShape->get_FillFormat()->set_FillType(FillType::Picture);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(watermarkImage);
watermarkShape->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);

presentation->Save(u"image-watermarked-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPT に透かしを追加する方法" intro="次の手順に従って、PPT ファイルにテキストまたは画像の透かしを追加します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPT ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation::get_Masters` コレクションからスライド マスターを選択します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` メソッドで透かしの図形を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` メソッドで透かしのテキストを追加するか、`AddImage` で画像の塗りつぶしを設定します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Ppt` で透かし入りのファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides で構築" title="PPT ファイルにオンラインで透かしを追加" description="無料の Aspose.Slides Watermark アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Watermark を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides が透かしをどう追加するかを確認できます。
- PPT ファイルにテキストまたは画像の透かしを追加できます。
- 透かし入りのファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="透かしに対応したその他の形式" subTitle="C++ では次の形式にも透かしを追加できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/watermark/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
