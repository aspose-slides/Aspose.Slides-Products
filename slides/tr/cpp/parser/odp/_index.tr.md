---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
weight: 460
title: C++ ile ODP sunularından metin çıkarma
url: /tr/cpp/parser/odp/ 
description: C++ ile ODP sunularından metin çıkarın. Slaytları, metin çerçevelerini, paragrafları ve metin parçalarını ayrıştırmak için Aspose.Slides for C++ kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ ile ODP sunularını ayrıştırma" h2="Microsoft PowerPoint olmadan sunu slaytlarından metin çıkarmak için Aspose.Slides for C++ kullanın."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://releases.aspose.com/slides/cpp/"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ ile ODP dosyasını ayrıştırma" %}}

ODP sunu dosyalarını ayrıştırmak ve slaytlardan metin çıkarmak için Aspose.Slides for C++ kullanın. API, slayt metnini `SlideUtil::GetAllTextBoxes`, `ITextFrame`, `IParagraph` ve `IPortion` üzerinden sunar; böylece Microsoft PowerPoint'i otomatikleştirmeden metin içeriğini okuyabilirsiniz. [`Aspose.Slides.Cpp`](https://www.nuget.org/packages/Aspose.Slides.Cpp/) paketini NuGet'ten yükleyin veya aşağıdaki komutu Paket Yöneticisi Konsolu'nda kullanın.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Komut" >}}
```powershell
PM> Install-Package Aspose.Slides.Cpp
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="ODP dosyalarını ayrıştırma – C++" >}}
```cpp
auto presentation = MakeObject<Presentation>(u"presentation.odp");
auto textFrames = SlideUtil::GetAllTextBoxes(presentation->get_Slide(0));

for (auto&& textFrame : textFrames)
{
    for (auto&& paragraph : textFrame->get_Paragraphs())
    {
        for (auto&& portion : paragraph->get_Portions())
        {
            Console::WriteLine(portion->get_Text());
        }
    }
}

presentation->Dispose();
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++ ile ODP dosyaları nasıl ayrıştırılır" intro="Aspose.Slides for C++ ile ODP dosyalarından metin çıkarın." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}ODP dosyasını `Presentation` sınıfıyla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İlk slaydın `ITextFrame` nesnelerini `SlideUtil::GetAllTextBoxes` ile alın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}`ITextFrame` nesneleri üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her `ITextFrame` içindeki `IParagraph` nesneleri üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her `IParagraph` içindeki `IPortion` nesneleri üzerinde dolaşın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Metni `get_Text` ile okuyun.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="Sistem gereksinimleri" intro="Aspose.Slides for C++ başlıca masaüstü ve sunucu platformlarını destekler. Projenizin aşağıdaki ön koşulları karşıladığından emin olun." %}}

-  Desteklenen C++ çalışma zamanına sahip Microsoft Windows, Linux, macOS veya uyumlu başka bir işletim sistemi.
-  Projenizde başvurulan Aspose.Slides for C++ kitaplığı.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/parser-app label="Aspose.Slides ile geliştirildi" title="Metin ve görüntüleri çevrimiçi çıkarın" description="Ücretsiz Aspose.Slides Parser uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi ODP dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Parser uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyalarınızı nasıl okuduğunu görün.
- Bir ODP dosyası yükleyin ve metnini ve görüntülerini alın.
- Her şeyi tek bir ZIP arşivi olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/parser-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" %}}

ODP dosyası, OpenOffice Impress ve LibreOffice Impress gibi uygulamaların kullandığı bir OpenDocument sunu dosyasıdır. Slaytları, metinleri, görüntüleri, biçimlendirmeyi, animasyonları ve diğer sunu içeriklerini açık, XML tabanlı bir pakette saklar.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Ayrıştırma için desteklenen diğer biçimler" subTitle="C++ ile başka sunu biçimlerini de ayrıştırabilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/parser/ppt/" name="PPT" description="PowerPoint 97-2003 Sunusu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="/slides/tr/cpp/parser/pptx/" name="PPTX" description="PowerPoint Open XML Sunusu" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
