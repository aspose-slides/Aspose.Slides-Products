---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java で PPTX プレゼンテーション ファイル内のテキストを検索
url: /ja/java/search/pptx/
description: Aspose.Slides for Java を使用して、Java で PPTX プレゼンテーション内のテキストを検索します。
keywords: PPTX 内の単語検索、PPTX 内のテキスト検索、PPTX プレゼンテーションのテキスト検索
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で PPTX 内のテキストを検索" h2="サーバー側 API でプレゼンテーション ファイル内のテキストを検索する Java アプリケーションを構築します。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java による PPTX プレゼンテーション内のテキスト検索" variant="code" %}}

[Aspose.Slides for Java](/slides/ja/java/) を使用すると、PPTX プレゼンテーション内のテキストを検索できます。`SlideUtil.getAllTextBoxes` メソッドでテキスト フレームを収集し、`ITextFrame`、`IParagraph`、`IPortion` オブジェクトを調べます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java で PPTX プレゼンテーション内のテキストを検索" >}}
```java
Presentation presentation = new Presentation("welcome-to-powerpoint.pptx");
try {
    String searchText = "PowerPoint";

    for (ISlide slide : presentation.getSlides()) {
        ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

        for (ITextFrame textFrame : slideTextFrames) {
            for (IParagraph paragraph : textFrame.getParagraphs()) {
                for (IPortion portion : paragraph.getPortions()) {
                    if (portion.getText().contains(searchText)) {
                        System.out.println(portion.getText());
                    }
                }
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java で PPTX 内のテキストを検索する方法" intro="PPTX プレゼンテーション内のテキストを検索するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.getAllTextBoxes` メソッドを呼び出して、各スライドのテキスト フレームを収集します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ITextFrame`、`IParagraph`、`IPortion` オブジェクトを調べて、一致するテキストを見つけます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/search-app label="Aspose.Slides で構築" title="PPTX ファイル内のテキストをオンラインで検索" description="無料の Aspose.Slides Search アプリは、上記のコードと同じ API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Search を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを見つけるしくみを確認できます。
- PPTX ファイル内をプレーン テキストまたは正規表現で検索できます。
- 検索結果をテキスト ファイルとしてダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/search-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="検索に対応するその他の形式" subTitle="Java では、次の形式でもテキストを検索できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/search/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
