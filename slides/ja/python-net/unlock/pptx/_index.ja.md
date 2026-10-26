---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Python で PPTX プレゼンテーションのロックを解除する
url: /ja/python-net/unlock/pptx/
description: Python で PPTX プレゼンテーションの暗号化と書き込み保護を解除します。
keywords: PPTX のロック解除, PPTX のパスワード解除, PPTX の暗号化解除, PPTX の書き込み保護解除
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Python で PPTX プレゼンテーションのロックを解除する" h2="Aspose.Slides で PPTX プレゼンテーションの読み取りパスワードと書き込み保護設定を解除する Python アプリケーションを構築できます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Python で PPTX の暗号化と書き込み保護を解除する" variant="code" %}}

[Aspose.Slides for Python via .NET](/slides/ja/python-net/) を使用すると、PPTX プレゼンテーションを開く際にパスワードを要求する暗号化を解除したり、書き込み保護の設定を解除したりできます。暗号化されたファイルを開くには、`LoadOptions` で現在のパスワードを指定します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX プレゼンテーションの暗号化を解除する – Python" >}}
```py
load_options = slides.LoadOptions()
load_options.password = "123123"

with slides.Presentation("encrypted-presentation.pptx", load_options) as presentation:
    presentation.protection_manager.remove_encryption()
    presentation.save("unencrypted-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX プレゼンテーションの書き込み保護を解除する – Python" >}}
```py
with slides.Presentation("write-protected-presentation.pptx") as presentation:
    presentation.protection_manager.remove_write_protection()
    presentation.save("unprotected-presentation.pptx", slides.export.SaveFormat.PPTX)
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Python で PPTX の保護を解除する方法" intro="PPTX プレゼンテーションの保護を解除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}暗号化された PPTX ファイルの場合は、`LoadOptions` に現在のパスワードを設定してから、`Presentation` でファイルを開きます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}読み取りパスワードを解除するには `ProtectionManager.remove_encryption` を、書き込み保護を解除するには `ProtectionManager.remove_write_protection` を呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.PPTX` を指定して、結果のプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides で構築" title="PPTX ファイルのロックをオンラインで解除する" description="無料の Aspose.Slides Unlock アプリは、上記のコードと同じ API である [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/ja/python-net/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Unlock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がどのように保護を解除するかを確認できます。
- PPTX ファイルからパスワードや書き込み保護を解除できます。
- ロックを解除したファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="ロック解除に対応しているその他の形式" subTitle="Python を使用して、サポートされているその他のプレゼンテーション形式の保護も解除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/python-net/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
