---
lastmod: 2026-10-25
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 3070
title: .NET ile ODP dosyalarından metin çıkarma
url: /tr/net/parser/odp/ 
description: .NET ile ODP dosyalarından metin çıkarmak için C# kaynak kodu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C# ile ODP dosyalarını ayrıştırma" h2="Sunucu tarafı .NET API'leriyle ODP dosyalarından metin çıkarın ve metin biçimlendirmesini inceleyin."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# ile ODP dosyasını ayrıştırma" %}}

ODP sunularından metin çıkarmak için [Aspose.Slides for .NET](/slides/tr/net/) kullanın. Paketi [NuGet](https://www.nuget.org/packages/aspose.slides.net) üzerinden yükleyin veya aşağıdaki komutu Paket Yöneticisi Konsolu'nda çalıştırın.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Komut" >}}
```powershell
PM> Install-Package Aspose.Slides.NET
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP dosyalarını ayrıştırma – C#" >}}
```cs
using var presentation = new Presentation("presentation.odp");
var textFrames = SlideUtil.GetAllTextFrames(presentation, true);

foreach (var textFrame in textFrames)
{
    foreach (var paragraph in textFrame.Paragraphs)
    {
        foreach (var portion in paragraph.Portions)
        {
            Console.WriteLine(portion.Text);
            Console.WriteLine(portion.PortionFormat.FontHeight);

            var latinFont = portion.PortionFormat.LatinFont;
            if (latinFont is not null)
            {
                Console.WriteLine(latinFont.FontName);
            }
        }
    }
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C# ile ODP dosyaları nasıl ayrıştırılır" intro="[Aspose.Slides for .NET](/slides/tr/net/) API'siyle temel belge ayrıştırma için yalnızca birkaç satır kod yeterlidir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Metin çerçevelerini `SlideUtil.GetAllTextFrames` ile alın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Metin çerçeveleri, paragraflar ve metin parçaları üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Gerektiğinde `Text`, `FontHeight` ve `LatinFont.FontName` özelliklerini okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Sistem gereksinimleri" intro="Desteklenen bir .NET çalışma zamanı ve Aspose.Slides for .NET paket başvurusu gerekir. Visual Studio'yu veya uyumlu başka bir C# geliştirme ortamını kullanabilirsiniz." %}}

- .NET Framework, .NET, Mono veya Xamarin uyumlu ortam
- Visual Studio gibi bir C# geliştirme ortamı
- NuGet'ten yüklenmiş Aspose.Slides for .NET

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides ile geliştirildi" title="Metin ve görüntüleri çevrimiçi çıkarın" description="Ücretsiz Aspose.Slides Parser uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Parser uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl okuduğunu görün.
- Bir ODP dosyası yükleyin ve metnini ve görüntülerini alın.
- Her şeyi tek bir ZIP arşivi olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP files use the OpenDocument Presentation format. A presentation contains slides with text, images, formatting, animations, and other media. Applications that support the OpenDocument format, such as OpenOffice and StarOffice, can open ODP files.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ayrıştırma için desteklenen diğer biçimler" subTitle="C# ile aşağıdaki biçimleri de ayrıştırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/parser/ppt/" name="PPT" description="PowerPoint 97-2003 Sunusu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/net/parser/pptx/" name="PPTX" description="PowerPoint Open XML Sunusu" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
