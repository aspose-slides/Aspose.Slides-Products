---
title: Python を使用して PPTX プレゼンテーション ファイルを保護する
url: /ja/python-net/protect/pptx/
keywords: 書き込み保護 PPTX、PPTX の暗号化、PPTX プレゼンテーションのロック、PPTX の保護
description: PPTX プレゼンテーションを保護するための Python ソース コード。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python を使用して PPTX をロックまたはパスワード保護する" h2="サーバー側 API を使用してプレゼンテーション ファイルを保護する独自の Python アプリを構築します。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python による PPTX プレゼンテーションの保護" %}}
Aspose.Slides for Python via .NET を使用すると、パスワードを設定して PPTX プレゼンテーションを開いたり変更したりできないように保護できます。次に、ロックされたプレゼンテーションを開くか変更するには、ユーザーはパスワードを入力する必要があります。
{{% blocks/products/pf/agp/code-block title="Python を使用して PPTX プレゼンテーションを暗号化する" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python を使用して PPTX プレゼンテーションに書き込み保護を設定する" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.pptx") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python 経由で PPTX をパスワード保護する方法" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="これらは、PPTX ファイルを保護するための手順です。" >}}

{{< blocks/products/pf/agp/step-autogen >}}
プレゼンテーションのインスタンスで PPTX を読み込みます
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager クラスを使用してプレゼンテーションを保護する
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
結果を PPTX 形式で保存
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="サポートされているその他のプロテクト形式" subTitle="Python を使用すると、次の形式も保護できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/ja/python-net/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}