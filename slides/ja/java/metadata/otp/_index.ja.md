---
title: Java を使用して OTP ファイルのメタデータを表示または編集する
url: /ja/java/metadata/otp/
keywords: OTP メタデータの編集、OTP メタデータの表示、OTP プロパティの編集、OTP プロパティの表示
description: Java ソース コードで、OTP 形式のメタデータを編集または表示できます。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java を使用して OTP プロパティを編集します" h2="独自の Java アプリを構築して、サーバー側 API を使用してプレゼンテーション ファイルの組み込みおよびカスタム プロパティを変更します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Java 経由で OTP プロパティを変更します" %}}
Aspose.Slides for Java を使用すると、開発者は組み込みプロパティとカスタム プロパティの値にアクセスして変更できます。開発者は、プレゼンテーション オブジェクトによって公開される [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) プロパティを使用して、プレゼンテーション ファイルのドキュメント プロパティにアクセスできます。
{{% blocks/products/pf/agp/code-block title="OTP 組み込みプロパティの変更 - Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.otp");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.otp", SaveFormat.Otp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="カスタム プロパティを OTP - Java に追加" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.otp", SaveFormat.Otp);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java 経由で OTP のメタデータを抽出する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、OTP ファイルからメタデータを抽出する手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
OTP ファイルへのパスを使用してプレゼンテーション クラスをインスタンス化する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションに関連付けられた DocumentProperties オブジェクトを取得する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
DocumentProperties オブジェクト内のアイテムをループする
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
カスタム プロパティへのアクセスと変更
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他のメタデータ形式" subTitle="Java を使用すると、他の多くの形式のメタデータを操作することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}