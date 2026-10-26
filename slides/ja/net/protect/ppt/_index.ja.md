---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET で PPT プレゼンテーション ファイルを保護する
url: /ja/net/protect/ppt/
description: PPT プレゼンテーションをパスワードで保護する C# ソースコード。
keywords: PPT 書き込み保護, PPT の暗号化, PPT プレゼンテーションのロック, PPT の保護
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# で PPT ファイルをロックまたはパスワード保護する" h2="サーバーサイド API でプレゼンテーションを暗号化し、変更を制限する .NET アプリを構築できます。" related="ODP,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# で PPT プレゼンテーションを保護する" variant="code" %}}

[Aspose.Slides for .NET](/slides/ja/net/) を使用すると、PPT プレゼンテーションを暗号化したり、パスワードで変更を制限したりできます。`ProtectionManager.Encrypt` で暗号化したプレゼンテーションを開くにはパスワードが必要です。`ProtectionManager.SetWriteProtection` を使用すると、プレゼンテーションを開くことは許可しつつ変更を制限できます。

{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で PPT プレゼンテーションを暗号化する" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.Encrypt("password");
presentation.Save("encrypted-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="C# で PPT プレゼンテーションに書き込み保護を設定する" >}}
```cs
using var presentation = new Presentation("presentation.ppt");
presentation.ProtectionManager.SetWriteProtection("password");
presentation.Save("write-protected-presentation.ppt", SaveFormat.Ppt);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# で PPT プレゼンテーションをパスワード保護する方法" intro="PPT プレゼンテーションをパスワードで保護するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` で PPT ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager.Encrypt` でプレゼンテーションを暗号化するか、`ProtectionManager.SetWriteProtection` で変更を制限します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Ppt` を指定して保護されたファイルを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/protect-app label="Aspose.Slides で構築" title="PPT ファイルをオンラインでパスワード保護する" description="無料の Aspose.Slides Lock アプリは、上記のコードと同じ API である [Aspose.Slides for .NET](https://products.aspose.com/slides/ja/net/) で構築されています。アプリを開いて、ご自身の PPT ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Lock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がプレゼンテーションをどのように保護するかを確認できます。
- PPT ファイルを開く、または編集するためのパスワードを設定できます。
- 保護されたファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/protect-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="保護に対応しているその他の形式" subTitle="C# を使用すると、次の形式も保護できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/net/protect/pptx/" name="PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
