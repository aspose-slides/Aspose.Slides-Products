---
title: C++ Kullanarak PDF, PPT, PPTX ve Diğer Birçok Dosya Formatını Birleştirin
url: /tr/cpp/merger/
keywords: Birleştir, Katıl, PowerPoint, Sunum, C++, Aspose
description: Birden çok dosyayı C++ PPT, PPTX, ODP, PDF, PNG, JPG ve daha pek çok yerde birleştirin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Powerpoint, PDF, PPT veya diğer belgeleri C++ ile birleştirin" h2="PPT, PPTX, PDF, PNG, JPEG ve diğer formatları birleştirmek için yüksek hızlı C++ kitaplığı." >}}

{{% blocks/products/pf/feature-page-section h2="C++ kullanarak PPT, PPTX, PDF'yi birleştirme" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) sunum dosyalarını oluşturmak ve değiştirmek için güçlü bir C++ kitaplığıdır. Ayrıca, birden fazla PPT/PPTX sunumunu birleştirmek için esnek yollar sağlar. Bir sunuyu diğeriyle birleştirdiğinizde, tek bir dosya elde etmek için slaytlarını tek bir sunuda etkili bir şekilde birleştirirsiniz. Aspose.Slides, iki sunumu farklı şekillerde birleştirmenize olanak tanır. Kalite veya veri kaybı konusunda endişelenmenize gerek kalmadan tüm şekilleri, stilleri, metinleri, biçimlendirmeleri, yorumları, animasyonları vb. ile sunuları birleştirebilirsiniz.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint sunumlarını C++ ile birleştirme" %}}
PowerPoint sunumlarını birleştirmek için slaytları bir sunumdan diğerine kopyalamanız gerekir.

{{% blocks/products/pf/agp/code-block title="PPTX dosyalarını C++ kullanarak birleştirme" offSpacer="true" %}}

```cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation2.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides())
{
	// Merge slides from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ kullanarak Sunuları Slide Master ile Birleştirme" %}}
Bu C++ kodu, birkaç sunumun nasıl bir araya getirildiğini ve ana slayt sunum şablonundan stillerin nasıl uygulandığını gösterir. Bu nedenle, sonuç sunumu aynı kaynak biçimlendirmesini koruyacak ve başka bir sunumun ana slaytından biçimlendirmeyi içerecektir.

{{% blocks/products/pf/agp/code-block title="Birden çok PPT'yi C++ ile tek olarak birleştirin" offSpacer="true" %}}

``` cpp

// The path to the documents directory.
const String sourceFilePath1 = u"SourceDirectory\\SamplePresentation.pptx";
const String sourceFilePath2 = u"SourceDirectory\\SamplePresentation3.pptx";
const String outputFilePath = u"OutputDirectory\\mergedPresentation.pptx";

// Load the presentation files
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

// Merge the first slide using slide master
presentation1->get_Slides()->AddClone(presentation2->get_Slides()->idx_get(0), presentation1->get_Masters()->idx_get(0), true);

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Aspose.Slides for C++ API kullanarak Sunumlar nasıl birleştirilir" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Bunlar, iki PPTX dosyasını birleştirme ve sonucu C++'da PDF olarak kaydetme adımlarıdır." >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for C++**](https://docs.aspose.com/slides/cpp/installation/) yükleyin. 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
C++ projenize bir kitaplık referansı ekleyin (kütüphaneyi içe aktarın).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kaynak PPTX dosyalarını C++ ile açın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
**AddClone** yöntemini kullanarak PPTX dosyalarını birleştirin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumu kaydedin ve sonucu tek bir PDF dosyası olarak alın.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Birleştirilecek Diğer Desteklenen Biçimler" subTitle="Diğer dosya biçimlerini de birleştirebilirsiniz. Aşağıdaki desteklenen diğer biçimlere bakın." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}