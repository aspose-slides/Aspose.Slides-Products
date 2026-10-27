---
lastmod: 2026-10-27
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPTM'yi PPTX'e dönüştürün
weight: 4320
url: /tr/java/conversion/pptm-to-pptx/ 
description: PPTM formatı için PPTX dosyasına örnek Java dönüştürme kodu. PowerPoint ve OpenOffice sunumlarını herhangi bir Web veya Masaüstü Java tabanlı Uygulama içinde PPTX'e aktarmak için bu örnek kodu kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPTM'yi PPTX'e dönüştürün" h2="PPTM'den PPTX'e Tek veya birden çok sayfayı Yerinde Java kitaplığı kullanarak PPTX'e dönüştürmek için Java dönüştürme."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java Kullanarak PPTM'yi PPTX'e Dönüştürme" %}}

PPTM'yi PPTX'e dönüştürmek için kullanacağız
 [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/)
 Java platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüştürme API'si olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="depo" >}}
```xml

<repository>
    <id>AsposeJavaAPI</id>
    <name>Aspose Java API</name>
    <url>https://releases.aspose.com/java/repo/</url>
</repository>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="Bağımlılık" >}}
```xml

<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-slides</artifactId>
    <version>26.8</version>
    <classifier>jdk16</classifier>
</dependency>
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPTM'den PPTX'e Java Dönüştürme Kaynak Kodu" >}}
```cs
// instantiate a Presentation object that represents a PPTM file
Presentation presentation = new Presentation("template.pptm");
// save the presentation as PPTX
presentation.save("output.pptx", SaveFormat.Pptx);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPTM'yi PPTX'e Dönüştürme Adımları" intro="Java geliştiricileri, PPTM dosyasını yalnızca birkaç satır kodla kolayca PPTX'e dönüştürebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTM dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu ve SaveFormat'ı belirtirken Presentation.save yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTX dosyası belirtilen yola kaydedilecektir.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="Java dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.
- Aspose.Slides for Java'nın en son sürümünü doğrudan Maven'den edinin.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/conversion-app label="Aspose.Slides ile geliştirildi" title="PPTM dosyasını çevrimiçi olarak PPTX biçimine dönüştürün" description="Ücretsiz Aspose.Slides Conversion uygulaması, yukarıdaki kodla aynı API olan [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java/) ile geliştirilmiştir. Uygulamayı açın ve API'nin kendi PPTM dosyalarınızla neler yapabildiğini görün." button="Aspose.Slides Conversion uygulamasını aç" note="[Tüm ücretsiz uygulamalar](https://products.aspose.app/slides/family)" upload="Dosyanızı bırakın veya yükleyin" saveAs="Farklı kaydet" convert="Dönüştür" >}}
- Tarayıcınızda çalışır, hiçbir şey yüklemeniz gerekmez.
- Kod yazmadan önce Aspose.Slides'ın dosyaları nasıl dönüştürdüğünü görün.
- PPTM dosyalarını yükleyin ve PPTX olarak kaydedin.
- Sonucu indirin veya daha fazla dosya dönüştürün.
{{< /blocks/products/pf/slides-design-update-10-2026/conversion-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPTM'yi aşağıda listelenen birkaç dosya formatı da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-bmp/" name="PPTM TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-gif/" name="PPTM TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-html/" name="PPTM TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-jpeg/" name="PPTM TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-odp/" name="PPTM TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-otp/" name="PPTM TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-pdf/" name="PPTM TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-png/" name="PPTM TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-pot/" name="PPTM TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-potm/" name="PPTM TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-potx/" name="PPTM TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-pps/" name="PPTM TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-ppsm/" name="PPTM TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-ppsx/" name="PPTM TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-ppt/" name="PPTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-svg/" name="PPTM TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-swf/" name="PPTM TO SWF" description="SWF Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-tiff/" name="PPTM TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/pptm-to-xps/" name="PPTM TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
