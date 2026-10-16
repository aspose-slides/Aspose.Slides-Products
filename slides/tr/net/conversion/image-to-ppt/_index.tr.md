---
lastmod: 2023-03-21
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Görüntüyü C# dilinde PPT'ye dönüştürün
url: /tr/net/conversion/image-to-ppt/
keywords: Görüntüyü PPT'ye, görüntüyü PPT'ye, PowerPoint'e, görüntüye, PPT'ye, C# API'ye, .NET Library'ye dönüştürün
description: Görüntüyü C# dilinde PPT'ye dönüştürün. Görüntüyü PowerPoint'e dönüştürmek için .NET kitaplık API'sini kullanın
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Görüntüyü C# dilinde PPT'ye dönüştürün" h2="NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında C# kodunu kullanarak görüntüyü PPT'ye dönüştürmek için güçlü çapraz platform .NET API'si" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Görüntüyü C# dilinde PPT'ye dönüştürün" variant="code" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/) kullanarak görüntüyü yalnızca birkaç satır kodla PowerPoint sunumuna dönüştürebilirsiniz:

{{< blocks/products/pf/slides-design-update-10-2026/code title="Görüntüyü PPT'ye dönüştürmek için C# kodu" >}}
```cs

using (Presentation pres = new Presentation())
{
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.jpg"));
    pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 720, 540, image);
    pres.Save("Presentation.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides kullanarak görüntüyü PPT'ye dönüştürün" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/tr/net/), PowerPoint sunumları, PDF'ler, HTML belgeleri, ve diğer dosyalar. Görüntüyü PPT'ye dönüştürdüğünüzde, aslında bu görüntülere dayalı slaytlar içeren bir PowerPoint sunusu oluşturmuş olursunuz.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="Görüntüyü C# dilinde PPT'ye dönüştürme" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET**'i kurun. Bakınız [**Kurulum**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize referans olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Presentation sınıfının bir örneğini oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPT'ye dönüştürmek istediğiniz görüntüyü yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Ortaya çıkan dosyayı bir PPT sunumu olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Ücretsiz Çevrimiçi Dönüştürücü"
  description="[Python'da PPT'yi HTML'ye Dönüştürme](https://products.aspose.com/slides/tr/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer Desteklenen PowerPoint Dönüşümleri" subTitle="Diğer biçimlerdeki dosyaları da PowerPoint'e dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/image-to-pptx/" name="IMAGE TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/jpg-to-ppt/" name="JPG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/jpg-to-pptx/" name="JPG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/png-to-ppt/" name="PNG TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/png-to-pptx/" name="PNG TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pdf-to-ppt/" name="PDF TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/pdf-to-pptx/" name="PDF TO PPTX" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/html-to-ppt/" name="HTML TO PPT" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
