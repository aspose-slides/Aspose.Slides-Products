---
title: Java kullanarak PPT Sunum Dosyalarında Metin Arayın
url: /tr/java/search/ppt/
keywords: kelimeleri PPT içinde ara, metni PPT içinde ara ve değiştir, metin ara PPT Sunum
description: PPT Sunumunda metin aramak için Java kaynak kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java kullanarak PPT Metni Arayın" h2="Sunucu tarafı API'lerini kullanarak sunum dosyalarındaki metni aramak ve değiştirmek için kendi Java uygulamalarınızı oluşturun. Sunum belgelerinde belirli bir kelimenin veya ifadenin tüm girişlerini nasıl bulacağınızı öğrenin. Tam veri eşleştirme ve düzenli ifade eşleştirmeye göre metin arayın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Metin Ara ve Değiştir PPT Java aracılığıyla sunum" %}}
Aspose.Slides for Java API'leri ile içeriklerde, yorumlarda, slayt notlarında veya meta verilerde temel bir belge arama ve metin değiştirme yalnızca birkaç satır kodla yapılabilir. Sunumda metin aramak için normal ifade eşleştirme, büyük/küçük harf eşleştirme kullanın. Başlıklarda, içerikte, altbilgide veya üstbilgide metin arayın.
{{% blocks/products/pf/agp/code-block title="Arama metni PPT Java kullanarak sunum" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.ppt");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.ppt", SaveFormat.Ppt);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Java Aracılığıyla PPT Metninde Nasıl Arama Yapılır?" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Metin PPT dosyalarını aramak için izlenecek adımlar bunlardır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Bir Sunum örneğiyle PPT yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Metni bulmak ve değiştirmek için [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) yöntemini kullanın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu PPT biçiminde kaydedin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi PPT Canlı Demoları Arayın" sectionDescription="PPT belgelerindeki içerikler, yorumlar veya meta verilerdeki metni hemen arayın ve değiştirin." >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Arama Biçimleri" subTitle="Java kullanarak, aşağıdaki biçimlerde de metin arayabilirsiniz:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}