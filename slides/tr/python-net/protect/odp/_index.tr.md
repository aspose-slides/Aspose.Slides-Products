---
title: Python kullanarak ODP Sunum Dosyalarını koruyun
url: /tr/python-net/protect/odp/
keywords: Yazma Koruması ODP, Bir ODP Şifreleme, ODP Sunumu Kilitleme, ODP Koruma
description: ODP Sunumunu korumak için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak ODP Kilitleyin veya Parolayla Koruyun" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarını korumak için kendi Python uygulamalarınızı oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Bir ODP Sunumunu Python Aracılığıyla Koruma" %}}
Aspose.Slides for Python via .NET kullanarak, bir şifre belirleyerek ODP sunumunuzu açılmaya veya değiştirilmeye karşı koruyabilirsiniz. Ardından, kilitli sunuyu açmak veya değiştirmek için kullanıcının parolayı sağlaması gerekir.
{{% blocks/products/pf/agp/code-block title="Bir ODP Sunumunu Python kullanarak şifreleme" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.encrypt("123123")
    pres.save("encrypted-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python kullanarak bir ODP Sunumuna Yazma Koruması Ayarlama" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("pres.odp") as pres:
    pres.protection_manager.set_write_protection("123123")
    pres.save("write-protected-pres.odp", slides.export.SaveFormat.ODP)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Aracılığıyla ODP Parola Koruması Nasıl Yapılır?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, ODP dosyalarını Koruma adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP dosyasını bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ProtectionManager sınıfını kullanarak sunuyu koruyun
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu ODP biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Koruma Biçimleri" subTitle="Python kullanarak aşağıdaki biçimleri de koruyabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/protect/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/protect/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}