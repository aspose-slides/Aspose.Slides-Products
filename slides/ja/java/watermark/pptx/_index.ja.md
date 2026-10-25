---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java で PPTX プレゼンテーション ファイルに透かしを追加
url: /ja/java/watermark/pptx/
description: Aspose.Slides for Java を使用して、Java で PPTX プレゼンテーションにテキストと画像の透かしを追加します。
keywords: PPTX に透かしを追加, PPTX にテキストの透かしを追加, PPTX に画像の透かしを追加
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で PPTX プレゼンテーションに透かしを追加する" h2="サーバー側 API を使用して、プレゼンテーション ファイルにテキストまたは画像の透かしを挿入する Java アプリケーションを構築します。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java による PPTX プレゼンテーションへの透かしの追加" variant="code" %}}

[Aspose.Slides for Java](/slides/ja/java/) を使用すると、PPTX プレゼンテーションにテキストと画像の透かしを追加できます。透かしの図形をスライド マスターに追加すると、そのマスターを使用するスライドに透かしが表示されます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java で PPTX にテキストの透かしを追加" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 400, 120);
    ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
    watermarkTextFrame.getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().setFontHeight(48);

    presentation.save("watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java で PPTX プレゼンテーションに画像の透かしを追加" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    byte[] imageData = Files.readAllBytes(Paths.get("watermark.png"));
    IPPImage watermarkImage = presentation.getImages().addImage(imageData);
    IMasterSlide masterSlide = presentation.getMasters().get_Item(0);
    IAutoShape watermarkShape = masterSlide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 200);

    watermarkShape.getFillFormat().setFillType(FillType.Picture);
    watermarkShape.getFillFormat().getPictureFillFormat().getPicture().setImage(watermarkImage);
    watermarkShape.getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);

    presentation.save("image-watermark.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java で PPTX に透かしを追加する方法" intro="次の手順に従って、PPTX ファイルにテキストまたは画像の透かしを追加します。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで `PPTX` ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`getMasters` メソッドでスライド マスターを選択します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`addAutoShape` メソッドを呼び出して透かしの図形を追加します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`addTextFrame` メソッドを呼び出して透かしのテキストを追加するか、画像の透かしには `addImage` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}透かし入りのプレゼンテーションを PPTX 形式で保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/watermark-app label="Aspose.Slides で構築" title="PPTX ファイルにオンラインで透かしを追加" description="無料の Aspose.Slides Watermark アプリは、上記のコードと同じ API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Watermark を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides が透かしをどう追加するかを確認できます。
- PPTX ファイルにテキストまたは画像の透かしを追加できます。
- 透かし入りのファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/watermark-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="透かしに対応したその他の形式" subTitle="Java では次の形式にも透かしを追加できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/watermark/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/watermark/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
