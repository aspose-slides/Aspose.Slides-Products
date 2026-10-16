---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java aracılığıyla PPSX'i PPTM'ye dönüştürün
weight: 3200
url: /tr/java/conversion/ppsx-to-pptm/ 
description: PPSX formatı için PPTM dosyasına örnek Java dönüştürme kodu. PowerPoint ve OpenOffice sunumlarını herhangi bir Web veya Masaüstü Java tabanlı Uygulama içinde PPTM'ye aktarmak için bu örnek kodu kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java aracılığıyla PPSX'i PPTM'ye dönüştürün" h2="PPSX'ten PPTM'ye Java dönüştürme, Yerinde Java kitaplığını kullanarak tekli veya çoklu sayfaları PPTM'ye dönüştürmek için."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java Kullanarak PPSX'i PPTM'ye Dönüştürme" %}}

PPSX'i PPTM'ye dönüştürmek için kullanacağız
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSX'ten PPTM'ye Java Dönüştürme Kaynak Kodu" >}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("template.ppsx");
// save the presentation as PPTM
presentation.save("output.pptm", SaveFormat.Pptm);   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPSX'i PPTM'ye Dönüştürme Adımları" intro="Java geliştiricileri, yalnızca birkaç satır kodla PPSX dosyasını kolayca PPTM'ye dönüştürebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSX dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Çıktı dosyası yolunu ve SaveFormat'ı belirtirken Presentation.save yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPTM dosyası belirtilen yola kaydedilecektir.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="Java dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.
- Aspose.Slides for Java'nın en son sürümünü doğrudan Maven'den edinin.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPSX 'a dönüştürmek için ücretsiz uygulama PPTM"
  description="[Ücretsiz Video uygulamamızı deneyin](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPSX'i aşağıda listelenen birkaç dosya formatı da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-bmp/" name="PPSX TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-gif/" name="PPSX TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-html/" name="PPSX TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-jpeg/" name="PPSX TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-odp/" name="PPSX TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-otp/" name="PPSX TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-pdf/" name="PPSX TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-png/" name="PPSX TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-pot/" name="PPSX TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-potm/" name="PPSX TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-potx/" name="PPSX TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-pps/" name="PPSX TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-ppsm/" name="PPSX TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-ppt/" name="PPSX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-pptx/" name="PPSX TO PPTX" description="Açık XML sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-svg/" name="PPSX TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-swf/" name="PPSX TO SWF" description="SWF Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-tiff/" name="PPSX TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsx-to-xps/" name="PPSX TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
