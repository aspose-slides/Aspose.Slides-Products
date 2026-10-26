---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPTX プレゼンテーションを保護する
url: /ja/cpp/protect/pptx/
description: C++ で PPTX プレゼンテーションを保護します。Aspose.Slides for C++ を使用して、ファイルを暗号化し、書き込み保護を設定できます。
keywords: PPTX 書き込み保護, PPTX の暗号化, PPTX プレゼンテーションのロック, PPTX の保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPTX をロックまたはパスワード保護する" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーションを暗号化し、書き込み保護を設定できます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で PPTX プレゼンテーションを保護する" variant="code" %}}

Aspose.Slides for C++ を使用すると、PPTX プレゼンテーションを開けないようにしたり、変更できないようにしたりできます。`Presentation` クラスの `ProtectionManager` オブジェクトを使用して、`Encrypt` でファイルを暗号化するか、`SetWriteProtection` で編集を制限します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPTX プレゼンテーションを暗号化する" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->Encrypt(u"password");
presentation->Save(u"encrypted-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPTX プレゼンテーションに書き込み保護を設定する" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.pptx");

presentation->get_ProtectionManager()->SetWriteProtection(u"password");
presentation->Save(u"write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPTX をパスワード保護する方法" intro="PPTX プレゼンテーションを保護するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` オブジェクトでプレゼンテーションを保護します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}パスワード保護には `Encrypt` を、書き込み保護には `SetWriteProtection` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Pptx` を指定して保護されたファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides で構築" title="PPTX ファイルをオンラインでパスワード保護する" description="無料の Aspose.Slides Lock アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Lock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がプレゼンテーションをどのように保護するかを確認できます。
- PPTX ファイルを開く、または編集するためのパスワードを設定できます。
- 保護されたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="保護に対応しているその他の形式" subTitle="C++ を使用すると、次の形式も保護できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/protect/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
