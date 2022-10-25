---
title: Java Kullanarak PDF, PPT, PPTX ve Diğer Birçok Dosya Formatını Birleştirin
url: /tr/java/merger/
keywords: Birleştir, Katıl, PowerPoint, Sunum, Java, Aspose
description: Java PPT, PPTX, ODP, PDF, PNG, JPG ve daha birçok dosyada birden fazla dosyayı birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java'da Powerpoint, PDF, PPT veya diğer belgeleri birleştirin" h2="PPT, PPTX, PDF, PNG, JPEG ve diğer formatları birleştirmek için yüksek hızlı Java kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="Java kullanarak PPT, PPTX, PDF'yi birleştirin" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/tr/java/) sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir Java kitaplığıdır. Ayrıca, birden fazla PPT/PPTX sunumunu birleştirmek için esnek yollar sağlar. Bir sunuyu diğeriyle birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunuda etkili bir şekilde birleştirirsiniz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenize olanak tanır. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile sunuları birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java'da PowerPoint sunumlarını birleştirme" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="Java kullanarak PPTX dosyalarını birleştirme" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Java kullanarak Slide Master ile Sunumları Birleştirme" %}}
Bu Java kodu, birkaç sunumun nasıl bir araya getirildiğini ve asıl slayt sunum şablonundan stillerin nasıl uygulandığını gösterir. Bu nedenle, sonuç sunumu aynı kaynak biçimlendirmesini koruyacak ve başka bir sunumun ana slaytından biçimlendirmeyi içerecektir.

{{% blocks/products/pf/agp/code-block title="Java'da birden çok PPT'yi tek olarak birleştirin" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for Java API kullanarak Sunumlar nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki PPTX dosyasını birleştirme ve sonucu Java'da PDF olarak kaydetme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for Java**](https://docs.aspose.com/slides/java/installation/) yükleyin. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Java projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPTX dosyalarını Java'da açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**addClone** yöntemini kullanarak PPTX dosyalarını birleştirin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek bir PDF dosyası olarak alın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Birleştirilecek Diğer Desteklenen Biçimler" subTitle="Diğer dosya biçimlerini de birleştirebilirsiniz. Aşağıdaki desteklenen diğer biçimlere bakın." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}