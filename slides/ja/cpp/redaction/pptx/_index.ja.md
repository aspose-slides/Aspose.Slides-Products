---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPTX プレゼンテーションを墨消し
url: /ja/cpp/redaction/pptx/
description: C++ で PPTX プレゼンテーションを墨消しします。Aspose.Slides for C++ を使用して、プレゼンテーション ファイル内の機密テキストを検索して置換します。
keywords: PPTX の墨消し、PPTX のテキスト検索と置換、PPTX プレゼンテーションの更新
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPTX を墨消し" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション ファイル内の機密テキストを検索して置換できます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ による PPTX プレゼンテーションの墨消し" variant="code" %}}

Aspose.Slides for C++ では、スライド内の機密テキストを置換することで PPTX プレゼンテーションを墨消しできます。`SlideUtil::FindAndReplaceText` と `Presentation` オブジェクトでプレゼンテーションを検索し、更新したファイルを保存する前に一致したテキストを置換します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ を使用した PPTX プレゼンテーションの墨消し" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"Confidential", u"[redacted]", nullptr);
presentation->Save(u"redacted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPTX を墨消しする方法" intro="PPTX プレゼンテーションを墨消しするには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}[`FindAndReplaceText`](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) メソッドを使用して、機密テキストを検索して置換します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}墨消ししたファイルを `SaveFormat::Pptx` で保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/redaction-app label="Aspose.Slides で構築" title="PPTX ファイルをオンラインで墨消し" description="無料の Aspose.Slides Redaction アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Redaction を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がテキストを検索して置換するしくみを確認できます。
- PPTX ファイル内のテキストを、正規表現も使って検索して置換できます。
- 墨消ししたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/redaction-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="墨消しに対応するその他の形式" subTitle="C++ では、次の形式も墨消しできます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/redaction/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
