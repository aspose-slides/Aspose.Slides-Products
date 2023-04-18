---
title: Python kullanarak ODP Açıklamasını Kaldırma
weight: 4380
url: /tr/python-net/annotation/odp/ 
description: ODP sunum yorumlarını kaldırmak için Python kaynak kodu
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python'da ODP'den Yorumları ve Yorum Yazarlarını Kaldırma" h2="Sunucu tarafı API'lerini kullanarak belge dosyalarındaki yorumları ve yazarları işlemek için kendi Python betiklerinizi oluşturun." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python aracılığıyla ODP'den Yorumları Kaldırma" %}}
Ek açıklamaları ODP dosyasından kaldırmak için zengin özelliklere sahip [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/tr/python-net/) API'sini kullanacağız, Python platformu için güçlü ve kullanımı kolay belge işleme API'si.
{{% blocks/products/pf/agp/code-block title="Ek Açıklamaları ODP'den Silme - Python" offSpacer="true" %}}

```python

import aspose.slides as slides

with slides.Presentation("example.odp") as presentation:
    # Deletes all comments from the presentation
    for author in presentation.comment_authors:
        author.comments.clear()

    # Deletes all authors
    presentation.comment_authors.clear()

    presentation.save("example_out.pptx", slides.export.SaveFormat.PPTX)
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Python ile ODP'den Yorumlar Nasıl Kaldırılır" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for Python'u .NET üzerinden** kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/python-net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP'yi bir Presentation sınıfı örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Yüklenen ODP'nin tüm Yazarlarını yineleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir yazarın tüm Yorumlarını kaldır
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonunda tüm Yazarları kaldır
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Ek Açıklama Biçimleri" subTitle="Python kullanılarak, aşağıdakiler de dahil olmak üzere diğer biçimlere kolayca açıklama eklenebilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}