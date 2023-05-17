---
title: C++ kullanarak ODP Sunum Dosyalarını Reddet
url: /tr/cpp/redaction/odp/
keywords: ODP dosyasını yeniden düzenleyin, ODP içindeki metni bulun ve değiştirin, ODP Sunumunu güncelleyin
description: ODP Sunumunda metin bulmak ve değiştirmek için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak ODP dosyasını yeniden düzenleyin" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni bulmak ve değiştirmek için kendi C++ uygulamalarınızı oluşturun. ODP sunularının içeriğindeki, yorumlarındaki veya meta verilerindeki metinleri nasıl arayacağınızı ve değiştireceğinizi öğrenin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ aracılığıyla ODP Sunumunu düzeltin" %}}
Aspose.Slides for C++ API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. PowerPoint ve OpenOffice'te metin bulun ve değiştirin. Normal ifade veri eşleştirme yoluyla sunumdaki metni, yorumları, meta verileri düzenleyin.
{{% blocks/products/pf/agp/code-block title="C++ kullanarak ODP Sunumunu düzeltin" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.odp");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.odp", SaveFormat::Odp);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla ODP Nasıl Redakte Edilir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, ODP dosyalarını Redakte etme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir Sunum örneğiyle ODP yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Metni bulmak ve değiştirmek için [FindAndReplaceText](https://reference.aspose.com/slides/cpp/aspose.slides.util/slideutil/findandreplacetext/) yöntemini kullanın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu ODP biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi ODP Redaksiyon Canlı Demoları" sectionDescription="ODP belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Redaksiyon Formatları" subTitle="C++ kullanarak aşağıdaki biçimleri de düzenleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}