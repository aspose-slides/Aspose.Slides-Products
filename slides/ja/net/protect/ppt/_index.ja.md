---
title: .NET を使用して PPT プレゼンテーション ファイルを保護する
url: /ja/net/protect/ppt/
keywords: 書き込み保護 PPT、PPT の暗号化、PPT プレゼンテーションのロック、PPT の保護
description: PPT プレゼンテーションを保護するための C# ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# を使用して PPT をロックまたはパスワード保護する" h2="サーバー側 API を使用してプレゼンテーション ファイルを保護する独自の .NET アプリを構築します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# による PPT プレゼンテーションの保護" %}}
Aspose.Slides for .NET を使用すると、パスワードを設定して PPT プレゼンテーションを開いたり変更したりできないように保護できます。次に、ロックされたプレゼンテーションを開くか変更するには、ユーザーはパスワードを入力する必要があります。
{{% blocks/products/pf/agp/code-block title="C# を使用して PPT プレゼンテーションを暗号化する" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# を使用して PPT プレゼンテーションに書き込み保護を設定する" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.ppt"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# 経由で PPT をパスワード保護する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPT ファイルを保護するための手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPT を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager クラスを使用してプレゼンテーションを保護する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPT 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他のプロテクト形式" subTitle="C# を使用すると、次の形式も保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}