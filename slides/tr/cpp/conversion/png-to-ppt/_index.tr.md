---
title: C++ ile PNG'yi PPT'ye dönüştürün
url: /tr/cpp/conversion/png-to-ppt/
keywords: PNG'yi PPT'ye, PNG'yi PPT'ye, PowerPoint'e, PNG'ye, PPT'ye, C++ API'ye, C++ Kitaplığına dönüştürün
description: C++ ile PNG'yi PPT'ye dönüştürün. PNG resimlerini PowerPoint'e dönüştürmek için C++ kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C++ ile PNG'yi PPT'ye dönüştürün" h2="C++ kodunu kullanarak PNG'yi PPT'ye dönüştürmek için güçlü platformlar arası C++ API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak PNG'yi PPT'ye dönüştürün" %}}

[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/), PowerPoint sunumları, PDF'ler, HTML belgeleri ve diğerlerini oluşturmak, dönüştürmek ve değiştirmek için kullanılan güçlü bir C++ kitaplığıdır. Dosyalar. PNG'yi PPT'ye dönüştürdüğünüzde, aslında PNG görüntülerine dayalı slaytlar içeren bir PowerPoint sunusu oluşturmuş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="C++ ile PNG'yi PPT'ye dönüştürün" %}}
[**Aspose.Slides for C++**](https://products.aspose.com/slides/tr/cpp/) kullanarak PNG görüntüsünü yalnızca birkaç satır kodla PowerPoint sunumuna dönüştürebilirsiniz:

{{% blocks/products/pf/agp/code-block title="PNG'yi PPT'ye dönüştürmek için C++ kodu" offSpacer="true" %}}
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto image = pres->get_Images()->AddImage(File::ReadAllBytes(u"image.png"));
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 720.0f, 540.0f, image);

pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PNG'yi C++ ile PPT'ye dönüştürme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for C++** yükleyin. Bakınız [**Kurulum**](https://docs.aspose.com/slides/cpp/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPT'ye dönüştürmek istediğiniz PNG görüntüsünü yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan dosyayı bir PPT sunumu olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen PowerPoint Dönüşümleri" subTitle="Diğer biçimlerdeki dosyaları da PowerPoint'e dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}