---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: .NET ile PPTM Dosyalarını Birleştirme
weight: 5580
url: /tr/net/merger/pptm/ 
description: PPTM belgelerini .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında birleştirmek için C# kaynak kodu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPTM Formatlarını C# ile Birleştirme" h2="Microsoft veya Open Office, Adobe PDF gibi herhangi bir yazılım kullanmadan sunucu tarafı Aspose.Slides for .NET API'lerini kullanan yerel ve yüksek performanslı PPTM belge birleştirme."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/net"
  learnLink="https://docs.aspose.com/slides/net"
  pricingLink="https://purchase.aspose.com/pricing/slides/net/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPT,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C# Kullanarak PPTM Dosyasını Birleştirme" %}}

PPTM dosyasını birleştirmek için kullanacağız
 [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net)
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay belge işleme ve birleştirme API'si olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 paket yöneticisi, ara
 **Aspose.Slides**
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Emretmek" >}}
```cs

PM> Install-Package Aspose.Slides.NET

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM Dosyalarını Birleştirme - C#" >}}
```cs
var ps1 = new Presentation("presen1.pptm");
    var ps2 = new Presentation("presen2.pptx");
    
    //merged Presentation 
    var mp = new Presentation("template.pptx");
    while (mp.Slides.Count > 0){
        mp.Slides.RemoveAt(0);
    }
    // master slide
    var ms = mp.Masters[0];
    
    // The first PPTM presentation is added with its own styles.
    foreach (var slide in ps1.Slides){
        mp.Slides.AddClone(slide);
    }
    
    // The second PPTX presentation is added with template presentation styles using.
    foreach (var slide in ps2.Slides){
        mp.Slides.AddClone(slide, ms, true);
    }
    
    // It is possible to save the merged presentation to any supported format.
    mp.Save("mp.pptx", SaveFormat.Pptx);
    mp.Save("mp.pptx", SaveFormat.Pdf);  

    

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PPTM Dosyalarını C# ile Birleştirme Adımları" intro="[Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net) API'lerini birleştiren ve birleştiren temel bir belge, yalnızca birkaç satır kodla yapılabilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Tüm PPTM dosyalarını tam yolla yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Temel dosya olarak bir belge yapın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Dosyaları tek tek birleştirmek ve birleştirmek için ilgili yöntemi çağırın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Save() yöntemini çağırın ve dosya adını (tam yol) ve formatı (PPTM) parametre olarak iletin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Artık PPTM dosyasını Microsoft Office, Adobe PDF veya diğer uyumlu programlarda açıp kullanabilirsiniz.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="API'lerimiz tüm büyük platformlarda ve İşletim Sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki ön koşulların bulunduğundan emin olun." %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi
- Microsoft Visual Studio gibi geliştirme ortamı
- Projenizde referans verilen .NET DLL için Aspose.Slides - Yukarıdaki İndir düğmesini kullanarak NuGet'ten yükleyin

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="merger" extension=""
  title="PDF Dosyalarını Çevrimiçi Birleştirme"
  description="[Python'da PDF Nasıl Birleştirilir](https://products.aspose.com/slides/tr/python-net/merge/pdf/)" >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPTM" readMoreLink="https://docs.fileformat.com/presentation/pptm/" %}}

`.PPTM` uzantılı dosyalar, Microsoft PowerPoint 2007 ile tanıtılan, makro desteği olan sunu dosyalarıdır. PPTX dosyalarına benzer, ancak PPTM dosyaları VBA makro kodu saklayabilirken PPTX dosyaları saklayamaz. PPTM dosyaları Microsoft PowerPoint'te açılıp düzenlenebilir. İlgili PPSM biçimi varsayılan olarak Slayt Gösterisi görünümünde açılır, ancak düzenleme için PowerPoint'te de açılabilir. PPTX dosyaları gibi PPTM dosyaları da metin, görüntü, video, grafik ve diğer sunu içeriklerini barındırabilir.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Birleştirme Formatları" subTitle="C# kullanarak One, dahil olmak üzere birçok başka dosya biçimini de birleştirebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/odp/" name="ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/otp/" name="OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/pot/" name="POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/potm/" name="POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/potx/" name="POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/pps/" name="PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/ppsm/" name="PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/ppsx/" name="PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/net/merger/pptx/" name="PPTX" description="Açık XML sunum Formatı" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
