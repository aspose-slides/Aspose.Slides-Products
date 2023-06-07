---
title: .NET kullanarak PPTX Sunum Dosyalarının Kilidini Açın
url: /tr/net/unlock/pptx/
keywords: PPTX Yazma Korumasını Kaldırma, Bir PPTX Şifresini Çözme, PPTX Sunumunun Kilidini Kaldırma, PPTX Korumasını Kaldırma
description: PPTX Sunumundan korumayı kaldırmak için C# kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# kullanarak PPTX kilidini açın" h2="PowerPoint'ten şifreleri kaldırmak ve sunucu tarafı API'lerini kullanarak sunum dosyalarının şifresini çözmek için kendi .NET uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# Aracılığıyla PPTX Sunumundan Şifrelemeyi Kaldırma" %}}
Aspose.Slides for .NET kullanarak, PPTX sunumundaki şifrelemeyi veya parola korumasını kaldırabilirsiniz. Bu şekilde, kullanıcılar kısıtlama olmadan PPTX sunumuna erişebilir veya sunuyu değiştirebilir.
{{% blocks/products/pf/agp/code-block title="C# kullanarak PPTX Şifre Korumasını devre dışı bırakma" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.pptx", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Kullanarak PPTX Sunumundan Yazma Korumasını Kaldırma" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# Aracılığıyla PPTX Ürününün Şifresini Kaldırma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarından korumayı kaldırma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak Yazma Korumasını kaldırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="C# kullanarak, aşağıdaki biçimlerden de korumayı kaldırabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}