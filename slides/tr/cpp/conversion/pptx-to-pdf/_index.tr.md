---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPTX'i C++ uygulamasıyla PDF'ye dönüştürün
weight: 8040
url: /tr/cpp/conversion/pptx-to-pdf/ 
description: PPTX belgesi için PDF formatına örnek C++ dönüştürme kodu. Herhangi bir C++ Uygulamasında toplu PPTX'ten PDF'ye dönüştürme için örnek kod kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTX'i C++ ile PDF'ye dönüştürün" h2="Microsoft PowerPoint kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı PPTX'ten PDF'ye dönüştürme."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ Kullanarak PPTX'i PDF'ye Dönüştürme" %}}

PPTX'i PDF'ye dönüştürmek için kullanacağız
 [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/)
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API'si olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 paket yöneticisi, ara
 Aspose.Slides.Cpp
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Emretmek" >}}
```cs

PM> Install-Package Aspose.Slides.Cpp

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTX'ten PDF'ye C++ Dönüştürme Kaynak Kodu" >}}
```cs
// Load the PPTX.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.pptx");
// Save in PDF format.
prs->Save(u"convertedFile.pdf", Aspose::Slides::Export::SaveFormat::Pdf);

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTX'i C++ ile PDF'ye Dönüştürme Adımları" intro="C++ geliştiricileri, PPTX dosyasını yalnızca birkaç satır kodla kolayca PDF'ye dönüştürebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyasını Aspose.Slides for C++ Presentation Object ile yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save() yöntemini çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu (PDF) dosya uzantısıyla iletin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF dosyası belirtilen yola kaydedilecektir.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PDF dosyasını uyumlu programda açın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.
- Projenizde referans verilen C++ DLL için Aspose.Slides.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPTX 'a dönüştürmek için ücretsiz uygulama PDF"
  description="[PPT için PDF dönüştürmek için ücretsiz uygulamamızı deneyin.](https://products.aspose.app/slides/conversion/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPTX'i aşağıda listelenen birkaç dosya formatı da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-png/" name="PPTX TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-svg/" name="PPTX TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-xml/" name="PPTX TO XML" description="Genişletilebilir İşaretleme Dili" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
