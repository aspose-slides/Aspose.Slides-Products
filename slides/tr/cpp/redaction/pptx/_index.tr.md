---
title: C++ kullanarak PPTX Sunum Dosyalarını Reddet
url: /tr/cpp/redaction/pptx/
keywords: PPTX dosyasını yeniden düzenleyin, PPTX içindeki metni bulun ve değiştirin, PPTX Sunumunu güncelleyin
description: PPTX Sunumunda metin bulmak ve değiştirmek için C++ kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C++ kullanarak PPTX dosyasını yeniden düzenleyin" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni bulmak ve değiştirmek için kendi C++ uygulamalarınızı oluşturun. PPTX sunularının içeriğindeki, yorumlarındaki veya meta verilerindeki metinleri nasıl arayacağınızı ve değiştireceğinizi öğrenin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}

{{% blocks/products/pf/feature-page-section  h2="C++ aracılığıyla PPTX Sunumunu düzeltin" %}}
Aspose.Slides for C++ API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. PowerPoint ve OpenOffice'te metin bulun ve değiştirin. Normal ifade veri eşleştirme yoluyla sunumdaki metni, yorumları, meta verileri düzenleyin.
{{% blocks/products/pf/agp/code-block title="C++ kullanarak PPTX Sunumunu düzeltin" offSpacer="true" %}}

```cpp

auto presentation = System::MakeObject<Presentation>(u"welcome-to-powerpoint.pptx");

SlideUtil::FindAndReplaceText(presentation, true, u"PowerPoint", u"Aspose.Slides", nullptr);
presentation->Save(u"replaced.pptx", SaveFormat::Pptx);	
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C++ Aracılığıyla PPTX Nasıl Redakte Edilir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPTX dosyalarını Redakte etme adımlarıdır." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPTX Redaksiyon Canlı Demoları" sectionDescription="PPTX belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Redaksiyon Formatları" subTitle="C++ kullanarak aşağıdaki biçimleri de düzenleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/redaction/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}