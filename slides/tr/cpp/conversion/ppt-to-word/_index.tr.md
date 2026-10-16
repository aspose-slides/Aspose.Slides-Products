---
lastmod: 2023-04-14
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C++ ile PPT'yi Word'e dönüştürün
url: /tr/cpp/conversion/ppt-to-word/
keywords: PPT'yi Word'e, PPT'yi Word'e, PPT'yi DOC'a, PowerPoint'i Word'e, C++ API'sini, C++ Kitaplığını, CPP'ye dönüştürün
description: PPT'yi C++'da Word'e dönüştürün. PowerPoint'i Word'e dönüştürmek için C++ kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile PPT'yi Word'e dönüştürün" h2="Microsoft PowerPoint veya Office olmadan C++ kodunu kullanarak PowerPoint'i Word'e dönüştürmek için güçlü platformlar arası C++ API'si" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PowerPoint'i C++ ile Word'e Dönüştürün" variant="code" %}}

Sadece birkaç satır kodla PPT'yi Word'e hızlı bir şekilde dönüştürebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PowerPoint'i Word'e dönüştürmek için C++ kodu" >}}
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
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides ve Aspose.Words kullanarak PowerPoint'i Word'e dönüştürün" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) ve [**Aspose.Words for C++**](https://products.aspose.com/ word/cpp/), PowerPoint sunumlarını, Word belgelerini ve diğer dosyaları değiştirmek ve dönüştürmek için kullanılan güçlü C++ kitaplıklarıdır. PowerPoint'i Word'e dönüştürdüğünüzde, aslında bir sunumun slaytlarının içeriğini bir Word belgesindeki sayfalara taşıyorsunuz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPT'i Word'e dönüştürme" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for C++** ve **Aspose.Words for C++** yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfı ve Doc sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Word'e dönüştürmek istediğiniz PPT sunumunu yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Slaytların içeriğine göre resimler ve metinler oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ortaya çıkan Word belgesini kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ücretsiz Çevrimiçi Dönüştürücü"
  description="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="PowerPoint'i başka biçimlerdeki dosyalara da dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/ppt-to-gif/" name="PPT TO GIF" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
