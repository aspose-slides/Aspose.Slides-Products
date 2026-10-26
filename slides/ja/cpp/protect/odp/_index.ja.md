---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で ODP プレゼンテーションを保護する
url: /ja/cpp/protect/odp/
description: C++ で ODP プレゼンテーションを保護します。Aspose.Slides for C++ を使用して、ファイルを暗号化し、書き込み保護を設定できます。
keywords: ODP 書き込み保護, ODP の暗号化, ODP プレゼンテーションのロック, ODP の保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で ODP をロックまたはパスワード保護する" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーションを暗号化し、書き込み保護を設定できます。" related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で ODP プレゼンテーションを保護する" variant="code" %}}

Aspose.Slides for C++ を使用すると、ODP プレゼンテーションを開けないようにしたり、変更できないようにしたりできます。`Presentation` クラスの `ProtectionManager` オブジェクトを使用して、`Encrypt` でファイルを暗号化するか、`SetWriteProtection` で編集を制限します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で ODP プレゼンテーションを暗号化する" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で ODP プレゼンテーションに書き込み保護を設定する" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.odp", SaveFormat::Odp);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で ODP をパスワード保護する方法" intro="ODP プレゼンテーションを保護するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで ODP ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` オブジェクトでプレゼンテーションを保護します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パスワード保護には `Encrypt` を、書き込み保護には `SetWriteProtection` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Odp` を指定して保護されたファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides で構築" title="ODP ファイルをオンラインでパスワード保護する" description="無料の Aspose.Slides Lock アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の ODP ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Lock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がプレゼンテーションをどのように保護するかを確認できます。
- ODP ファイルを開く、または編集するためのパスワードを設定できます。
- 保護されたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="保護に対応しているその他の形式" subTitle="C++ を使用すると、次の形式も保護できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
