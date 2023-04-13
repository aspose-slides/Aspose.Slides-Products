---
title: C++ ile PPT'yi Word'e dönüştürün
url: /tr/cpp/conversion/ppt-to-word/
keywords: PPT'yi Word'e, PPT'yi Word'e, PPT'yi DOC'a, PowerPoint'i Word'e, C++ API'sini, C++ Kitaplığını, CPP'ye dönüştürün
description: PPT'yi C++'da Word'e dönüştürün. PowerPoint'i Word'e dönüştürmek için C++ kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ ile PPT'yi Word'e dönüştürün" h2="Microsoft PowerPoint veya Office olmadan C++ kodunu kullanarak PowerPoint'i Word'e dönüştürmek için güçlü platformlar arası C++ API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides ve Aspose.Words kullanarak PowerPoint'i Word'e dönüştürün" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) ve [**Aspose.Words for C++**](https://products.aspose.com/ word/cpp/), PowerPoint sunumlarını, Word belgelerini ve diğer dosyaları değiştirmek ve dönüştürmek için kullanılan güçlü C++ kitaplıklarıdır. PowerPoint'i Word'e dönüştürdüğünüzde, aslında bir sunumun slaytlarının içeriğini bir Word belgesindeki sayfalara taşıyorsunuz.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PowerPoint'i C++ ile Word'e Dönüştürün" %}}
Sadece birkaç satır kodla PPT'yi Word'e hızlı bir şekilde dönüştürebilirsiniz.

{{% blocks/products/pf/agp/code-block title="PowerPoint'i Word'e dönüştürmek için C++ kodu" offSpacer="true" %}}
```cpp
auto presentation = MakeObject<Presentation>();
auto doc = MakeObject<Aspose::Words::Document>();
auto builder = MakeObject<Aspose::Words::DocumentBuilder>(doc);

for (const auto& slide : presentation->get_Slides())
{
    // generates and inserts slide image
    auto bitmap = slide->GetThumbnail(1.0f, 1.0f);
    builder->InsertImage(bitmap);

    // inserts slide's texts
    for (const auto& shape : slide->get_Shapes())
    {
        if (ObjectExt::Is<AutoShape>(shape))
        {
            auto autoShape = System::AsCast<AutoShape>(shape);
            builder->Writeln(autoShape->get_TextFrame()->get_Text());
        }
    }

    builder->InsertBreak(Aspose::Words::BreakType::PageBreak);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PPT'i Word'e dönüştürme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** ve **Aspose.Words for C++** yükleyin 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfı ve Doc sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Word'e dönüştürmek istediğiniz PPT sunumunu yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Slaytların içeriğine göre resimler ve metinler oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan Word belgesini kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="PowerPoint'i başka biçimlerdeki dosyalara da dönüştürebilirsiniz." >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}