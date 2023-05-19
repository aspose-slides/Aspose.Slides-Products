---
title: C++ kullanarak PPTX Sunum Dosyalarında Metin Arayın
url: /tr/cpp/search/pptx/
keywords: kelimeleri PPTX içinde ara, metni PPTX içinde ara ve değiştir, metin ara PPTX Sunum
description: PPTX Sunumunda metin aramak için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak PPTX Metni Arayın" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni aramak ve değiştirmek için kendi C++ uygulamalarınızı oluşturun. Sunum belgelerinde belirli bir kelimenin veya ifadenin tüm girişlerini nasıl bulacağınızı öğrenin. Tam veri eşleştirme ve düzenli ifade eşleştirmeye göre metin arayın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="Metin Ara ve Değiştir PPTX C++ aracılığıyla sunum" %}}
Aspose.Slides for C++ API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. Sunumda metin aramak için normal ifade eşleştirme, büyük/küçük harf eşleştirme kullanın. Başlıklarda, içerikte, altbilgide veya üstbilgide metin arayın.
{{% blocks/products/pf/agp/code-block title="Arama metni PPTX C++ kullanarak sunum" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPTX Metninde Nasıl Arama Yapılır?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Metin PPTX dosyalarını aramak için izlenecek adımlar bunlardır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir Sunum örneğiyle PPTX yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Metni bulmak ve değiştirmek için [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) yöntemini kullanın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPTX biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPTX Canlı Demoları Arayın" sectionDescription="PPTX belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Arama Biçimleri" subTitle="C++ kullanarak, aşağıdaki biçimlerde de metin arayabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}