---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# で PPTX プレゼンテーションに透かしを追加
url: /ja/net/watermark/pptx/
description: Aspose.Slides for .NET を使用して、C# で PPTX プレゼンテーションにテキストと画像の透かしを追加します。
keywords: PPTX に透かしを追加, PPTX にテキストの透かしを追加, PPTX に画像の透かしを追加
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で PPTX プレゼンテーションに透かしを追加する" h2="プレゼンテーション ファイルにテキストまたは画像の透かしを挿入する .NET アプリケーションを構築します。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# による PPTX プレゼンテーションへの透かしの追加" variant="code" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用すると、PPTX プレゼンテーションにテキストと画像の透かしを追加できます。透かしの図形をスライド マスターに追加すると、そのマスターを使用するスライドに透かしが表示されます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で PPTX にテキストの透かしを追加" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
var watermarkTextFrame = watermarkShape.AddTextFrame("Watermark");
watermarkTextFrame.Paragraphs[0].Portions[0].PortionFormat.FontHeight = 48;

presentation.Save("watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で PPTX プレゼンテーションに画像の透かしを追加" >}}
```cs
using var presentation = new Presentation("presentation.pptx");

var imageData = File.ReadAllBytes("watermark.png");
var watermarkImage = presentation.Images.AddImage(imageData);
var masterSlide = presentation.Masters[0];
var watermarkShape = masterSlide.Shapes.AddAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

watermarkShape.FillFormat.FillType = FillType.Picture;
watermarkShape.FillFormat.PictureFillFormat.Picture.Image = watermarkImage;
watermarkShape.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;

presentation.Save("image-watermarked-presentation.pptx", SaveFormat.Pptx);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で PPTX に透かしを追加する方法" intro="次の手順に従って、PPTX ファイルにテキストまたは画像の透かしを追加します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで `PPTX` ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation.Masters` コレクションからスライド マスターを選択します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddAutoShape` メソッドを呼び出して透かしの図形を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`AddTextFrame` メソッドを呼び出して透かしのテキストを追加するか、画像の透かしには `AddImage` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pptx` で透かし入りのファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides で構築" title="PPTX ファイルにオンラインで透かしを追加" description="無料の Aspose.Slides Watermark アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Watermark を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides が透かしをどう追加するかを確認できます。
- PPTX ファイルにテキストまたは画像の透かしを追加できます。
- 透かし入りのファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="透かしに対応したその他の形式" subTitle="C# では次の形式にも透かしを追加できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
