---
title: Java を使用して PPT プレゼンテーション ファイルのロックを解除します
url: /ja/java/unlock/ppt/
keywords: 書き込み保護 PPT を削除、PPT を復号化、PPT プレゼンテーションのロックを解除、PPT の保護を解除
description: Java ソース コードを使用して、PPT プレゼンテーションから保護を削除します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java を使用して PPT のロックを解除する" h2="独自の Java アプリを構築して、PowerPoint からパスワードを削除し、サーバー側 API を使用してプレゼンテーション ファイルを復号化します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java 経由で PPT プレゼンテーションから暗号化を削除しています" %}}
Aspose.Slides for Java を使用すると、PPT プレゼンテーションの暗号化またはパスワード保護を削除できます。このようにして、ユーザーは制限なく PPT プレゼンテーションにアクセスしたり変更したりできるようになります。
{{% blocks/products/pf/agp/code-block title="Java を使用して PPT からのパスワード保護を無効にする" offSpacer="true" %}}

```java

LoadOptions loadOptions = new LoadOptions();
loadOptions.setPassword("123123");
Presentation presentation = new Presentation("pres.ppt", loadOptions);
try {
    presentation.getProtectionManager().removeEncryption();
    presentation.save("encryption-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java を使用して PPT プレゼンテーションから書き込み保護を削除します" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.ppt");
try {
    presentation.getProtectionManager().removeWriteProtection();
    presentation.save("write-protection-removed.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java 経由で PPT からパスワードを削除する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPT ファイルから保護を削除する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPT を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager クラスを使用して書き込み保護を削除する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPT 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている形式" subTitle="Java を使用すると、次の形式から保護を削除することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}