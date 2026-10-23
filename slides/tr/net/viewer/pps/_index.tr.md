---
lastmod: 2026-10-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: C# ile PPS görüntüleme
keywords: PPS görüntüle, PPS aç, PPS görüntüleyici, PPS, PowerPoint, C# API, .NET kütüphanesi
weight: 7110
url: /tr/net/viewer/pps/ 
description: C# ile PPS dosyalarını görüntüleyin. Sunu dosyalarını açmak ve HTML olarak kaydetmek için Aspose.Slides for .NET kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile PPS görüntüleme" h2="PPS dosyalarını açmak ve duyarlı HTML olarak kaydetmek için C# API'si."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPSM,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Aspose.Slides ile PPS görüntüleme" %}}

PPS dosyalarını görüntülemek için C# için güçlü, zengin özellikli ve kullanımı kolay bir API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) API'sini kullanın. [NuGet](https://www.nuget.org/packages/aspose.slides.net) paket yöneticisini açın, **Aspose.Slides** paketini arayın ve yükleyin. Aşağıdaki komutu Paket Yöneticisi Konsolu'nda da çalıştırabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Paket Yöneticisi Konsolu komutu" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

[**Aspose.Slides for .NET**](/slides/tr/net/) ile birkaç satır kodla bir PPS dosyasını yükleyebilir ve duyarlı HTML olarak kaydedebilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPS görüntülemek için C# kodu" >}}
```cs
using var presentation = new Presentation("presentation.pps");

var responsiveHtmlController = new ResponsiveHtmlController();
var htmlOptions = new HtmlOptions
{
    HtmlFormatter = HtmlFormatter.CreateCustomFormatter(responsiveHtmlController)
};

presentation.Save("output.html", SaveFormat.Html, htmlOptions);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile PPS nasıl görüntülenir" intro="Aspose.Slides, geliştiricilerin PPS dosyalarını yalnızca birkaç satır kodla görüntülemesini sağlar." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}**Aspose.Slides for .NET** kütüphanesini yükleyin. Bkz. [**Kurulum**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Kütüphaneyi projenize başvuru olarak ekleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`PPS` dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Duyarlı HTML çıktısı için bir `ResponsiveHtmlController` nesnesi oluşturun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Bir `HtmlOptions` nesnesi oluşturun ve `HtmlFormatter` özelliğini ayarlayın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPS dosyasını `SaveFormat.Html` ile HTML olarak kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Sistem gereksinimleri" intro="Aspose.Slides for .NET tüm önemli işletim sistemlerini destekler. Aşağıdaki ön koşulları karşıladığınızdan emin olun." %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono ya da Xamarin ile uyumlu bir işletim sistemi
- Microsoft Visual Studio gibi bir geliştirme ortamı
- Projenizde Aspose.Slides for .NET başvurusu

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/viewer-app label="Aspose.Slides ile geliştirildi" title="PPS Dosyalarını Çevrimiçi Görüntüleyin" description="Ücretsiz Aspose.Slides Viewer uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPS dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Viewer uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl görüntülediğini görün.
- PPS dosyanızı yükleyin ve slaytlarını anında görüntüleyin.
- PowerPoint gerekmeden masaüstünde ve mobilde çalışır.
{{< /blocks/products/pf/slides-design-update-10-2026/viewer-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPS" readMoreLink="https://docs.fileformat.com/presentation/pps/" %}}

PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. The more latest version of this file format is PPSX which is based on Office OpenXML standards. PPS files can still be read by latest versions of Microsoft PowerPoint, but newly created files can only be saved in PPSX file format. When a PPS file is shared with another user and opened, it starts as Powerpoint show unlike PPT file which opens in editable mode.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Diğer dosyaları görüntüleyin" subTitle="Diğer biçimlerdeki sunuları da açıp görüntüleyebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/odp/" name="ODP" description="OpenDocument Sunusu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/otp/" name="OTP" description="OpenDocument Sunu Şablonu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/pot/" name="POT" description="PowerPoint 97-2003 Şablonu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/potm/" name="POTM" description="Makro İçerebilen PowerPoint Şablonu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/potx/" name="POTX" description="PowerPoint Şablonu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/ppsm/" name="PPSM" description="Makro İçerebilen PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/ppsx/" name="PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/ppt/" name="PPT" description="PowerPoint 97-2003 Sunusu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/pptm/" name="PPTM" description="Makro İçerebilen PowerPoint Sunusu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/viewer/pptx/" name="PPTX" description="PowerPoint Sunusu" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
