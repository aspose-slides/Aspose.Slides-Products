---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: Java ile PPSM'yi BMP'ye dönüştürün
weight: 3980
url: /tr/java/conversion/ppsm-to-bmp/ 
description: PPSM formatı için BMP dosyasına örnek Java dönüştürme kodu. PowerPoint ve OpenOffice sunumlarını herhangi bir Web veya Masaüstü Java tabanlı Uygulama içinde BMP'ye aktarmak için bu örnek kodu kullanın.
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="Java ile PPSM'yi BMP'ye dönüştürün" h2="PPSM'den BMP'ye Java dönüştürme, Yerinde Java kitaplığını kullanarak tek veya birden çok sayfayı BMP'ye dönüştürmek için."
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/java"
  learnLink="https://docs.aspose.com/slides/java"
  pricingLink="https://purchase.aspose.com/pricing/slides/java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Java Kullanarak PPSM'yi BMP'ye Dönüştürme" %}}

PPSM'yi BMP'ye dönüştürmek için kullanacağız
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

{{< blocks/products/pf/slides-design-update-10-2026/code title="PPSM'den BMP'ye Java Dönüştürme Kaynak Kodu" >}}
```cs
// load PPSM with Aspose.Slides
Presentation presentation = new Presentation("template.ppsm");
   
    // iterate over all slides in the presentation
for (ISlide sld : presentation.getSlides()) 
{
  
  // create a full scale image of each slide
  BufferedImage bi = sld.getThumbnail(new RenderingOptions());

  // create a new file of type BMP for every slide
  File outputfile = new File(sld.getSlideNumber() + ".bmp");
  
  // save the slide image to disk
  ImageIO.write(bi, "bmp", outputfile);
}   

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="Java ile PPSM'yi BMP'ye Dönüştürme Adımları" intro="Java geliştiricileri, PPSM dosyasını yalnızca birkaç satır kodla kolayca BMP'ye dönüştürebilir." >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PPSM dosyasını bir Presentation sınıfı örneğiyle yükleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Sunumdaki her Slaytı yineleyin{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Her yinelemede Bitmap olarak tam ölçekli bir görüntü oluşturun{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}BMP dosya uzantısı ve ImageFormat ile Bitmap.save yöntemini çağırın{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{% blocks/products/pf/slides-design-update-10-2026/requirements title="sistem gereksinimleri" intro="Java dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun." %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.
- Aspose.Slides for Java'nın en son sürümünü doğrudan Maven'den edinin.

{{% /blocks/products/pf/slides-design-update-10-2026/requirements %}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="PPSM 'a dönüştürmek için ücretsiz uygulama BMP"
  description="[PPT için BMP dönüştürmek için ücretsiz uygulamamızı deneyin.](https://products.aspose.app/slides/conversion/ppt-to-bmp)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPSM'yi aşağıda listelenen birkaç dosya formatı da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-gif/" name="PPSM TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-html/" name="PPSM TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-jpeg/" name="PPSM TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-odp/" name="PPSM TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-otp/" name="PPSM TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-pdf/" name="PPSM TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-png/" name="PPSM TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-pot/" name="PPSM TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-potm/" name="PPSM TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-potx/" name="PPSM TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-pps/" name="PPSM TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-ppsx/" name="PPSM TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-ppt/" name="PPSM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-pptm/" name="PPSM TO PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-pptx/" name="PPSM TO PPTX" description="Açık XML sunum Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-svg/" name="PPSM TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-swf/" name="PPSM TO SWF" description="SWF Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-tiff/" name="PPSM TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/tr/java/conversion/ppsm-to-xps/" name="PPSM TO XPS" description="XML Kağıt Özellikleri" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
