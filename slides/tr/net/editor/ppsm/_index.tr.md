---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET aracılığıyla PPSM dosyalarını düzenleyin
url: /tr/net/editor/ppsm/ 
description: .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında PPSM belgesini düzenlemek için C# kaynak kodu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPSM Formatlarını C# ile Düzenle" h2="Microsoft veya Adobe PDF gibi herhangi bir yazılım kullanmadan sunucu taraflı Aspose.Slides for .NET API'lerini kullanarak yerel ve yüksek performanslı PPSM belge düzenleme."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="HTML,ODP,OTP,PDF,POT,POTM,POTX,PPS,PPSX,PPT,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# Kullanarak PPSM Dosyası Nasıl Düzenlenir" %}}

PPSM dosyasını düzenlemek için zengin özelliklere sahip, güçlü bir <a href="https://products.aspose.com/slides/tr/net">Aspose.Slides for .NET</a> API'sini kullanacağız. ve herhangi bir düzenleyici için C# platformu için kullanımı kolay API. <a href="https://www.nuget.org/packages/aspose.slides.net">NuGet</a> paket yöneticisini açın, <b>Aspose.Slides</b>'i arayın ve kurun. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Emretmek" >}}
```cs

PM> Install-Package Aspose.Slides

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM Dosyalarını Düzenle - C#" >}}
```cs
using var presentation = new Presentation("document.ppsm");
var slide = presentation.Slides[0];

if (slide.Shapes[0] is IAutoShape shape && shape.TextFrame is not null)
{
    shape.TextFrame.Text = "New text";
}

presentation.Save("document.ppsm", SaveFormat.Ppsm);
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPSM Dosyalarını C# ile Düzenleme Adımları" intro="ile temel bir belge düzenleme [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net) API'ler sadece birkaç satır kodla yapılabilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSM dosyasını bir `Presentation` nesnesiyle yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Hedef slayta ve şekle değişkenler aracılığıyla erişin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Metni `TextFrame` aracılığıyla güncelleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Düzenlenen sunuyu `SaveFormat.Ppsm` ile kaydedin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="API'lerimiz tüm büyük platformlarda ve İşletim Sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki ön koşulların bulunduğundan emin olun." %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi
- Microsoft Visual Studio gibi geliştirme ortamı
- Projenizde referans verilen .NET DLL için Aspose.Slides - Yukarıdaki İndir düğmesini kullanarak NuGet'ten yükleyin

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Aspose.Slides ile geliştirildi" title="PPTX Dosyalarını Çevrimiçi Düzenleyin" description="Ücretsiz Aspose.Slides Editor uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTX dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Editor uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl işlediğini görün.
- PPTX dosyalarınızı yükleyin ve anında düzenleyin.
- Düzenlenen dosyayı kaydedin ve indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" %}}

PPSM uzantılı dosyalar, makro desteği olan PowerPoint slayt gösterisi dosyalarıdır. Slayt gösterisi olarak açılır ve slaytlar, multimedya, biçimlendirme ve makrolar içerebilir.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
