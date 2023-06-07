---
title: .NET kullanarak ODP Sunum Dosyalarının Kilidini Açın
url: /tr/net/unlock/odp/
keywords: ODP Yazma Korumasını Kaldırma, Bir ODP Şifresini Çözme, ODP Sunumunun Kilidini Kaldırma, ODP Korumasını Kaldırma
description: ODP Sunumundan korumayı kaldırmak için C# kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# kullanarak ODP kilidini açın" h2="PowerPoint'ten şifreleri kaldırmak ve sunucu tarafı API'lerini kullanarak sunum dosyalarının şifresini çözmek için kendi .NET uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# Aracılığıyla ODP Sunumundan Şifrelemeyi Kaldırma" %}}
Aspose.Slides for .NET kullanarak, ODP sunumundaki şifrelemeyi veya parola korumasını kaldırabilirsiniz. Bu şekilde, kullanıcılar kısıtlama olmadan ODP sunumuna erişebilir veya sunuyu değiştirebilir.
{{% blocks/products/pf/agp/code-block title="C# kullanarak ODP Şifre Korumasını devre dışı bırakma" offSpacer="true" %}}

```cs

LoadOptions loadOptions = new LoadOptions {Password = "123123"};
using (Presentation presentation = new Presentation("pres.odp", loadOptions))
{
    presentation.ProtectionManager.RemoveEncryption();
    presentation.Save("encryption-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Kullanarak ODP Sunumundan Yazma Korumasını Kaldırma" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("pres.odp"))
{
    presentation.ProtectionManager.RemoveWriteProtection();
    presentation.Save("write-protection-removed.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# Aracılığıyla ODP Ürününün Şifresini Kaldırma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, ODP dosyalarından korumayı kaldırma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak Yazma Korumasını kaldırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu ODP biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="C# kullanarak, aşağıdaki biçimlerden de korumayı kaldırabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/unlock/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}