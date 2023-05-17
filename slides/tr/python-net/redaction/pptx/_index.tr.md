---
title: Python kullanarak PPTX Sunum Dosyalarını Reddet
url: /tr/python-net/redaction/pptx/
keywords: PPTX dosyasını yeniden düzenleyin, PPTX içindeki metni bulun ve değiştirin, PPTX Sunumunu güncelleyin
description: PPTX Sunumunda metin bulmak ve değiştirmek için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak PPTX dosyasını yeniden düzenleyin" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni bulmak ve değiştirmek için kendi Python uygulamalarınızı oluşturun. PPTX sunularının içeriğindeki, yorumlarındaki veya meta verilerindeki metinleri nasıl arayacağınızı ve değiştireceğinizi öğrenin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Python aracılığıyla PPTX Sunumunu düzeltin" %}}
Aspose.Slides for Python via .NET API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. PowerPoint ve OpenOffice'te metin bulun ve değiştirin. Normal ifade veri eşleştirme yoluyla sunumdaki metni, yorumları, meta verileri düzenleyin.
{{% blocks/products/pf/agp/code-block title="Python kullanarak PPTX Sunumunu düzeltin" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPTX Nasıl Redakte Edilir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarını Redakte etme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir Sunum örneğiyle PPTX yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Metni bulmak ve değiştirmek için [FindAndReplaceText](https://reference.aspose.com/slides/python-net/aspose.slides.util/slideutil/) yöntemini kullanın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPTX Redaksiyon Canlı Demoları" sectionDescription="PPTX belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Redaksiyon Formatları" subTitle="Python kullanarak aşağıdaki biçimleri de düzenleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}