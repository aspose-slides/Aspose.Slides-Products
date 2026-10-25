---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 7140
title: Java で PPT ドキュメントからテキストを抽出
url: /ja/java/parser/ppt/ 
description: Aspose.Slides for Java を使用して、Java で PPT ファイルからテキストを抽出します。
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で PPT ファイルを解析" h2="Aspose.Slides for Java のサーバー側 API を使用して、PPT ドキュメントからテキストとプレゼンテーションの内容を抽出します。"
  apiHomeLink="/slides/java/"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/java/"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/"
  related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java で PPT ファイルを解析" %}}

[Aspose.Slides for Java](/slides/ja/java/) を使用して PPT プレゼンテーションを解析し、スライドからテキストを抽出します。Maven ベースのプロジェクトにライブラリを追加するには、`pom.xml` ファイルに次のリポジトリと依存関係の設定を追加します。

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="リポジトリ" >}}
```xml
<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="依存関係" >}}
```xml
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT ファイルの解析 - Java" >}}
```java
Presentation presentation = new Presentation("demo.ppt");
try {
    ISlide slide = presentation.getSlides().get_Item(0);
    ITextFrame[] slideTextFrames = SlideUtil.getAllTextBoxes(slide);

    for (ITextFrame textFrame : slideTextFrames) {
        for (IParagraph paragraph : textFrame.getParagraphs()) {
            for (IPortion portion : paragraph.getPortions()) {
                System.out.print(portion.getText());
                System.out.print(portion.getPortionFormat().getFontHeight());
                System.out.print(portion.getPortionFormat().getLatinFont().getFontName());
            }
        }
    }
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java で PPT ファイルを解析する方法" intro="Aspose.Slides for Java を使用すると、数行のコードで PPT プレゼンテーションからテキストを抽出できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで `PPT` ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SlideUtil.getAllTextBoxes` メソッドを呼び出して、最初のスライドのテキスト フレームを取得します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各 `ITextFrame`、`IParagraph`、`IPortion` オブジェクトを順に処理します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}各 `IPortion` オブジェクトからテキスト、フォント サイズ、フォント名を読み取ります。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="システム要件" intro="Aspose.Slides for Java は主要なプラットフォームとオペレーティング システムをサポートしています。環境が次の前提条件を満たしていることを確認してください。" %}}

- JSP/JSF アプリケーションおよびデスクトップ アプリケーション用の Java Runtime Environment を備えた Microsoft Windows または互換 OS。
- [Maven](https://releases.aspose.com/java/repo/) から入手できる最新バージョンの Aspose.Slides for Java。

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides で構築" title="テキストと画像をオンラインで抽出" description="無料の Aspose.Slides Parser アプリは、上記のコードと同じ API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Parser を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がファイルをどう読み取るかを確認できます。
- PPT ファイルをアップロードして、テキストと画像を取得できます。
- すべてを 1 つの ZIP アーカイブでダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

A PPT file stores a PowerPoint 97-2003 presentation in the binary file format. It can contain slides with text, images, charts, multimedia, and embedded objects.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="その他の解析可能な形式" subTitle="Java では他のプレゼンテーション形式も解析できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/parser/odp/" name="ODP" description="OpenDocument プレゼンテーション" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/parser/pptx/" name="PPTX" description="PowerPoint Open XML プレゼンテーション" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
