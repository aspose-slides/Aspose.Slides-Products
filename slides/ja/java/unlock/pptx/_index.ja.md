---
lastmod: 2026-10-26
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java で PPTX プレゼンテーション ファイルのロックを解除する
url: /ja/java/unlock/pptx/
description: Aspose.Slides for Java を使用して、Java で PPTX プレゼンテーションからパスワードと書き込み保護を解除します。
keywords: PPTX 書き込み保護の解除, PPTX の復号, PPTX プレゼンテーションのロック解除, PPTX の保護解除
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java で PPTX のロックを解除する" h2="サーバーサイド API でプレゼンテーション ファイルのパスワードと書き込み保護を解除する Java アプリケーションを構築できます。" related="ODP,PPT" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java で PPTX プレゼンテーションの保護を解除する" variant="code" %}}

[Aspose.Slides for Java](/slides/ja/java/) を使用すると、PPTX プレゼンテーションの暗号化や書き込み保護を解除できます。暗号化されたプレゼンテーションを開くには `LoadOptions.setPassword` を使用し、保護設定を解除するには `ProtectionManager` の `removeEncryption` メソッドと `removeWriteProtection` メソッドを使用します。

{{< blocks/products/pf/slides-design-update-10-2026/code title="Java で PPTX のパスワード保護を解除する" >}}
```java
LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");

Presentation presentation = new Presentation("presentation.pptx", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Java で PPTX プレゼンテーションの書き込み保護を解除する" >}}
```java
Presentation presentation = new Presentation("presentation.pptx");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.pptx", SaveFormat.Pptx);
} finally {
    presentation.dispose();
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java で PPTX からパスワードを解除する方法" intro="PPTX プレゼンテーションの保護を解除するには、次の手順に従います。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`Presentation` クラスで PPTX ファイルを読み込みます。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}プレゼンテーションが暗号化されている場合は、`LoadOptions.setPassword` を使用します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ProtectionManager` オブジェクトの `removeEncryption` または `removeWriteProtection` を呼び出します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`SaveFormat.Pptx` を指定して、ロックを解除したプレゼンテーションを保存します。{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/unlock-app label="Aspose.Slides で構築" title="PPTX ファイルのロックをオンラインで解除する" description="無料の Aspose.Slides Unlock アプリは、上記のコードと同じ API である [Aspose.Slides for Java](https://products.aspose.com/slides/ja/java/) で構築されています。アプリを開いて、ご自身の PPTX ファイルで API に何ができるかをお確かめください。" button="Aspose.Slides Unlock を開く" note="[すべての無料アプリ](https://products.aspose.app/slides/family)" >}}
- ブラウザーで動作し、インストールは不要です。
- コードを書く前に、Aspose.Slides がどのように保護を解除するかを確認できます。
- PPTX ファイルからパスワードや書き込み保護を解除できます。
- ロックを解除したファイルをダウンロードできます。
{{< /blocks/products/pf/slides-design-update-10-2026/unlock-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="ロック解除に対応しているその他の形式" subTitle="Java を使用すると、次の形式の保護も解除できます。" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/ja/java/unlock/ppt/" name="PPT" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
