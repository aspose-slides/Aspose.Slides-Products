---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPT プレゼンテーションを墨消し
url: /ja/cpp/redaction/ppt/
description: C++ で PPT プレゼンテーションを墨消しします。Aspose.Slides for C++ を使用して、プレゼンテーション ファイル内の機密テキストを検索して置換します。
keywords: PPT の墨消し、PPT のテキスト検索と置換、PPT プレゼンテーションの更新
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPT を墨消し" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション ファイル内の機密テキストを検索して置換できます。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ による PPT プレゼンテーションの墨消し" variant="code" %}}

Aspose.Slides for C++ では、スライド内の機密テキストを置換することで PPT プレゼンテーションを墨消しできます。`SlideUtil::FindAndReplaceText` と `Presentation` オブジェクトでプレゼンテーションを検索し、更新したファイルを保存する前に一致したテキストを置換します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ を使用した PPT プレゼンテーションの墨消し" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.ppt");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.ppt", SaveFormat::Ppt);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPT を墨消しする方法" intro="PPT プレゼンテーションを墨消しするには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPT ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) メソッドを使用して、機密テキストを検索して置換します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}墨消ししたファイルを `SaveFormat::Ppt` で保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides で構築" title="PPT ファイルをオンラインで墨消し" description="無料の Aspose.Slides Redaction アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Redaction を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを検索して置換するしくみを確認できます。
- PPT ファイル内のテキストを、正規表現も使って検索して置換できます。
- 墨消ししたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="墨消しに対応するその他の形式" subTitle="C++ では、次の形式も墨消しできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/redaction/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
