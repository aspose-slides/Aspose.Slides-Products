---
title: Python kullanarak PPTX Sunum Dosyalarının Kilidini Açın
url: /tr/python-net/unlock/pptx/
keywords: PPTX Yazma Korumasını Kaldırma, Bir PPTX Şifresini Çözme, PPTX Sunumunun Kilidini Kaldırma, PPTX Korumasını Kaldırma
description: PPTX Sunumundan korumayı kaldırmak için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak PPTX kilidini açın" h2="PowerPoint'ten şifreleri kaldırmak ve sunucu tarafı API'lerini kullanarak sunum dosyalarının şifresini çözmek için kendi Python uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPTX Sunumundan Şifrelemeyi Kaldırma" %}}
Aspose.Slides for Python via .NET kullanarak, PPTX sunumundaki şifrelemeyi veya parola korumasını kaldırabilirsiniz. Bu şekilde, kullanıcılar kısıtlama olmadan PPTX sunumuna erişebilir veya sunuyu değiştirebilir.
{{% blocks/products/pf/agp/code-block title="Python kullanarak PPTX Şifre Korumasını devre dışı bırakma" offSpacer="true" %}}

```py

import aspose.slides as slides

loadOptions = slides.LoadOptions()
loadOptions.password = "123123"
with slides.Presentation("encrypted-pres.pptx", loadOptions) as pres:
    pres.protection_manager.remove_encryption()
    pres.save("encryption-removed.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python Kullanarak PPTX Sunumundan Yazma Korumasını Kaldırma" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("write-protected-pres.pptx") as pres:
    pres.protection_manager.remove_write_protection()
    pres.save("write-protection-removed.pptx", slides.export.SaveFormat.PPTX)

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPTX Ürününün Şifresini Kaldırma" >}}

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

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Formatlar" subTitle="Python kullanarak, aşağıdaki biçimlerden de korumayı kaldırabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/unlock/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/unlock/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}