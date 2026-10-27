---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT Dosyalarını C++ ile Birleştirme
weight: 4840
url: /tr/cpp/merger/ppt/ 
description: Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment'da PPT belgelerini birleştirmek için C++ örnek kodu.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="C++ kullanarak PPT Dosyalarını Birleştirme" h2="Sunucu tarafı C++ API'lerini kullanarak PPT belge birleştirme."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/cpp"
  learnLink="https://docs.aspose.com/slides/cpp"
  pricingLink="https://purchase.aspose.com/pricing/slides/cpp/"
  related="ODP,OTP,POT,POTM,POTX,PPS,PPSM,PPSX,PPTM,PPTX" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="C++ Kullanarak PPT Dosyasını Birleştirme" %}}

PPT dosyasını birleştirmek için kullanacağız
 [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/)
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge birleştirme API'si olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 paket yöneticisi, ara
 **Aspose.Slides.Cpp**
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPT Dosyalarını Birleştirme - C++" >}}
```cs
// The path to the documents directory.
const String sourceFilePath1 = u"SourceFile2.ppt";
const String sourceFilePath2 = u"SourceFile3.ppt";
const String outputFilePath = u"mergedOutput.ppt";

// Instantiate Presentation class
SharedPtr<Presentation> presentation1 = MakeObject<Presentation>(sourceFilePath1);
SharedPtr<Presentation> presentation2 = MakeObject<Presentation>(sourceFilePath2);

for (SharedPtr<ISlide> slide : presentation2->get_Slides()){
	// Merge from source to destination 
	presentation1->get_Slides()->AddClone(slide);
}

// Save the presentation
presentation1->Save(outputFilePath, SaveFormat::Ppt);  

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="C++'da PPT Dosyalarını Birleştirme Adımları" intro="[Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) API'lerini birleştiren ve birleştiren temel bir belge, yalnızca birkaç satır kodla yapılabilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her iki PPT dosyasını da yükleyin.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her slaytta yineleme yapmak için get\_Slides() yöntemini kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}İstediğiniz dosyayla birleştirmek için AddClone işlevini kullanın.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Belirtilen yola kaydetmek için Save() yöntemini kullanın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="Aspose.Slides for C++ tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.
- Projenizde referans verilen C++ DLL için Aspose.Slides.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/merger-app label="Aspose.Slides ile geliştirildi" title="PPT dosyalarını çevrimiçi birleştirin" description="Ücretsiz Aspose.Slides Merger uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPT dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Merger uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl birleştirdiğini görün.
- Birden fazla PPT dosyası yükleyin ve bunları tek bir dosyada birleştirin.
- Birleştirilmiş sonucu tek bir dosya olarak indirin.
{{< /blocks/products/pf/slides-design-update-10-2026/merger-app >}}

{{% blocks/products/pf/slides-design-update-10-2026/about-format format="PPT" readMoreLink="https://docs.fileformat.com/presentation/ppt/" %}}

.ppt uzantılı bir dosya, slayt gösterisinde kullanılacak slaytları içeren bir PowerPoint sunusudur. Microsoft PowerPoint 97–2003 tarafından desteklenen ikili dosya biçimini kullanır. Bir PPT dosyası metin, madde işaretli listeler, görüntüler, multimedya ve diğer gömülü OLE nesneleri gibi çeşitli içerik türleri barındırabilir. Microsoft, PowerPoint 2007 ile bu ikili biçim yerine Office Open XML'i temel alan daha yeni PPTX biçimini tanıttı. OpenOffice Impress ve Apple Keynote gibi başka uygulamalar da PPT dosyaları oluşturabilir.

{{% /blocks/products/pf/slides-design-update-10-2026/about-format %}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Birleştirme Formatları" subTitle="C++ kullanarak One, aşağıdakiler de dahil olmak üzere diğer birçok dosya biçimini birleştirebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/odp/" name="ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/otp/" name="OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/pot/" name="POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/potm/" name="POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/potx/" name="POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/pps/" name="PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/ppsm/" name="PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/ppsx/" name="PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/pptm/" name="PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/cpp/merger/pptx/" name="PPTX" description="Açık XML sunum Formatı" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
