---
title: C# dilinde JPG'yi PPTX'e dönüştürme
url: /tr/net/conversion/jpg-to-pptx/
keywords: JPG'yi PPTX'e, JPG'yi PPTX'e, PowerPoint, JPG, PPTX, C# API, .NET Library'ye dönüştürün
description: C# dilinde JPG'yi PPTX'e dönüştürün. JPG resimlerini PowerPoint'e dönüştürmek için .NET kitaplık API'sini kullanın
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="C# dilinde JPG'yi PPTX'e dönüştürme" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodunu kullanarak JPG'yi PPTX'e dönüştürmek için güçlü çapraz platform .NET API'si" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides kullanarak JPG'yi PPTX'e dönüştürün" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), PowerPoint sunumları, PDF'ler, HTML belgeleri, ve diğer dosyalar. JPG'yi PPTX'e dönüştürdüğünüzde, aslında JPG görüntülerine dayalı slaytlar içeren bir PowerPoint sunusu oluşturmuş olursunuz.

{{% /blocks/products/pf/feature-page-section %}}


{{% blocks/products/pf/feature-page-section  h2="C# dilinde JPG'yi PPTX'e dönüştürme" %}}
[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) kullanarak JPG görüntüsünü yalnızca birkaç satır kodla PowerPoint sunumuna dönüştürebilirsiniz:

{{% blocks/products/pf/agp/code-block title="JPG'yi PPTX'e dönüştürmek için C# kodu" offSpacer="true" %}}
```cs
using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="C# dilinde JPG'yi PPTX'e dönüştürme" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for .NET**'i kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kütüphaneyi projenize referans olarak ekleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Presentation sınıfının bir örneğini oluşturun.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX'e dönüştürmek istediğiniz JPG görüntüsünü yükleyin.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ortaya çıkan dosyayı bir PPTX sunumu olarak kaydedin.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Ücretsiz Çevrimiçi Dönüştürücü" sectionDescription="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen PowerPoint Dönüşümleri" subTitle="Diğer biçimlerdeki dosyaları da PowerPoint'e dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}