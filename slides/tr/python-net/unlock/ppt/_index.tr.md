---
title: Python kullanarak PPT Sunum Dosyalarının Kilidini Açın
url: /tr/python-net/unlock/ppt/
keywords: PPT Yazma Korumasını Kaldırma, Bir PPT Şifresini Çözme, PPT Sunumunun Kilidini Kaldırma, PPT Korumasını Kaldırma
description: PPT Sunumundan korumayı kaldırmak için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak PPT kilidini açın" h2="PowerPoint'ten şifreleri kaldırmak ve sunucu tarafı API'lerini kullanarak sunum dosyalarının şifresini çözmek için kendi Python uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPT Sunumundan Şifrelemeyi Kaldırma" %}}
Aspose.Slides for Python via .NET kullanarak, PPT sunumundaki şifrelemeyi veya parola korumasını kaldırabilirsiniz. Bu şekilde, kullanıcılar kısıtlama olmadan PPT sunumuna erişebilir veya sunuyu değiştirebilir.
{{% blocks/products/pf/agp/code-block title="Python kullanarak PPT Şifre Korumasını devre dışı bırakma" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.ppt", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.ppt", slides.export.SaveFormat.PPT)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python Kullanarak PPT Sunumundan Yazma Korumasını Kaldırma" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.ppt") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.ppt", slides.export.SaveFormat.PPT)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPT Ürününün Şifresini Kaldırma" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPT dosyalarından korumayı kaldırma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak Yazma Korumasını kaldırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="Python kullanarak, aşağıdaki biçimlerden de korumayı kaldırabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/unlock/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}