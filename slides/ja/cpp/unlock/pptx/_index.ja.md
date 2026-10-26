---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ で PPTX プレゼンテーションのロックを解除する
url: /ja/cpp/unlock/pptx/
description: C++ で PPTX プレゼンテーションのロックを解除します。Aspose.Slides for C++ を使用して、プレゼンテーション ファイルの暗号化と書き込み保護を解除できます。
keywords: PPTX 書き込み保護の解除, PPTX の復号, PPTX プレゼンテーションのロック解除, PPTX の保護解除
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ で PPTX のロックを解除する" h2="Aspose.Slides for C++ を使用すると、Microsoft PowerPoint なしでプレゼンテーション ファイルの暗号化と書き込み保護を解除できます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ で PPTX プレゼンテーションの保護を解除する" variant="code" %}}

Aspose.Slides for C++ を使用すると、PPTX プレゼンテーションの暗号化や書き込み保護を解除できます。暗号化されたファイルを `LoadOptions` で開き、`Presentation` クラスの `ProtectionManager` オブジェクトを使用して `RemoveEncryption` または `RemoveWriteProtection` を呼び出します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPTX のパスワード保護を解除する" >}}
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_Password(u"password");

auto presentation = MakeObject<Presentation>(u"encrypted-presentation.pptx", loadOptions);

presentation->get_ProtectionManager()->RemoveEncryption();
presentation->Save(u"unlocked-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C++ で PPTX プレゼンテーションの書き込み保護を解除する" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"write-protected-presentation.pptx");

presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"unlocked-write-protected-presentation.pptx", SaveFormat::Pptx);
presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ で PPTX からパスワードを解除する方法" intro="PPTX プレゼンテーションの保護を解除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。パスワードが必要な場合は `LoadOptions` も使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` オブジェクトを使用して保護を解除します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}暗号化されたファイルには `RemoveEncryption` を、書き込み保護されたファイルには `RemoveWriteProtection` を呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat::Pptx` を指定して、ロックを解除したファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides で構築" title="PPTX ファイルのロックをオンラインで解除する" description="無料の Aspose.Slides Unlock アプリは、上記のコードと同じ API である [Aspose.Slides for C++](https://products.aspose.com/slides/ja/cpp/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Unlock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がどのように保護を解除するかを確認できます。
- PPTX ファイルからパスワードや書き込み保護を解除できます。
- ロックを解除したファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="ロック解除に対応しているその他の形式" subTitle="C++ を使用すると、次の形式の保護も解除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/cpp/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
