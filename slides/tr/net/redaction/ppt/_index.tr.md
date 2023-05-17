---
title: .NET kullanarak PPT Sunum Dosyalarını Reddet
url: /tr/net/redaction/ppt/
keywords: PPT dosyasını yeniden düzenleyin, PPT içindeki metni bulun ve değiştirin, PPT Sunumunu güncelleyin
description: PPT Sunumunda metin bulmak ve değiştirmek için C# kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# kullanarak PPT dosyasını yeniden düzenleyin" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni bulmak ve değiştirmek için kendi .NET uygulamalarınızı oluşturun. PPT sunularının içeriğindeki, yorumlarındaki veya meta verilerindeki metinleri nasıl arayacağınızı ve değiştireceğinizi öğrenin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="C# aracılığıyla PPT Sunumunu düzeltin" %}}
Aspose.Slides for .NET API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. PowerPoint ve OpenOffice'te metin bulun ve değiştirin. Normal ifade veri eşleştirme yoluyla sunumdaki metni, yorumları, meta verileri düzenleyin.
{{% blocks/products/pf/agp/code-block title="C# kullanarak PPT Sunumunu düzeltin" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="C# Aracılığıyla PPT Nasıl Redakte Edilir?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, PPT dosyalarını Redakte etme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir Sunum örneğiyle PPT yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Metni bulmak ve değiştirmek için [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) yöntemini kullanın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPT Redaksiyon Canlı Demoları" sectionDescription="PPT belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Redaksiyon Formatları" subTitle="C# kullanarak aşağıdaki biçimleri de düzenleyebilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/redaction/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}