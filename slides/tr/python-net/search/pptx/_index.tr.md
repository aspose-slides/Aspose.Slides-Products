---
title: Python kullanarak PPTX Sunum Dosyalarında Metin Arayın
url: /tr/python-net/search/pptx/
keywords: kelimeleri PPTX içinde ara, metni PPTX içinde ara ve değiştir, metin ara PPTX Sunum
description: PPTX Sunumunda metin aramak için Python kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Python kullanarak PPTX Metni Arayın" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni aramak ve değiştirmek için kendi Python uygulamalarınızı oluşturun. Sunum belgelerinde belirli bir kelimenin veya ifadenin tüm girişlerini nasıl bulacağınızı öğrenin. Tam veri eşleştirme ve düzenli ifade eşleştirmeye göre metin arayın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-python.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Python via .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Python via .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Metin Ara ve Değiştir PPTX Python aracılığıyla sunum" %}}
Aspose.Slides for Python via .NET API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. Sunumda metin aramak için normal ifade eşleştirme, büyük/küçük harf eşleştirme kullanın. Başlıklarda, içerikte, altbilgide veya üstbilgide metin arayın.
{{% blocks/products/pf/agp/code-block title="Arama metni PPTX Python kullanarak sunum" offSpacer="true" %}}

```py

import aspose.slides as slides

with slides.Presentation("welcome-to-powerpoint.pptx") as pres:
    slides.util.SlideUtil.find_and_replace_text(pres, True, "PowerPoint", "Aspose.Slides", None)
    pres.save("replaced.pptx", slides.export.SaveFormat.PPTX)
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Python Aracılığıyla PPTX Metninde Nasıl Arama Yapılır?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Metin PPTX dosyalarını aramak için izlenecek adımlar bunlardır." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPTX Canlı Demoları Arayın" sectionDescription="PPTX belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Arama Biçimleri" subTitle="Python kullanarak, aşağıdaki biçimlerde de metin arayabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/python-net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}