---
title: ODP'yi Java aracılığıyla PPSM'ye dönüştürün
weight: 5170
url: /tr/java/conversion/odp-to-ppsm/ 
description: ODP formatı için PPSM dosyasına örnek Java dönüştürme kodu. PowerPoint ve OpenOffice sunumlarını herhangi bir Web veya Masaüstü Java tabanlı Uygulama içinde PPSM'ye aktarmak için bu örnek kodu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="ODP'yi Java aracılığıyla PPSM'ye dönüştürün" h2="ODP'den PPSM'ye Java dönüştürme, tek veya birden çok sayfayı Yerinde Java kitaplığı kullanarak PPSM'ye dönüştürmek için." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak ODP'yi PPSM'ye Dönüştürme" %}}

 ODP'yi PPSM'ye dönüştürmek için kullanacağız
 [Aspose.Slides for Java](https://products.aspose.com/slides/java)
 Java platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüştürme API'si olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides)
 ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="depo" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bağımlılık" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-slides</artifactId>
<version>version of aspose-slides API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ODP'yi Java ile PPSM'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java geliştiricileri, ODP dosyasını yalnızca birkaç satır kodla kolayca PPSM'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. ODP dosyasını bir Presentation sınıfı örneğiyle yükleyin
1. Çıktı dosyası yolunu ve SaveFormat'ı belirtirken Presentation.save yöntemini çağırın
1. PPSM dosyası belirtilen yola kaydedilecektir.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.
- Aspose.Slides for Java'nın en son sürümünü doğrudan Maven'den edinin.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ODP'den PPSM'ye Java Dönüştürme Kaynak Kodu" offSpacer="" %}}

```cs
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("template.odp");
// save the presentation as PPSM
presentation.save("output.ppsm", SaveFormat.Ppsm);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ODP to PPSM Conversion Live Demos" sectionDescription="[Convert ODP to PPSM](https://products.aspose.app/slides/conversion/odp-to-ppsm) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your ODP file, it will be converted instantly to PPSM." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Java Sunum Manipülasyon Kitaplığı" %}}

 Slides and Presentation API, Microsoft PowerPoint belgelerini okumak, yazmak, değiştirmek ve PDF, XPS, HTML, TIFF, ODP ve diğer çeşitli biçimlere dönüştürmek için kullanılabilir. Sıfırdan yeni dosyalar oluşturabilir ve bunları ilgili desteklenen biçimlerde kaydedebilirsiniz. Aspose.Slides, sunumlar, slaytlar ve öğeler oluşturmak, ayrıştırmak veya değiştirmek için bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılıma bağlı değildir.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}

Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSM" readMoreLink="https://docs.fileformat.com/presentation/ppsm/" >}}

Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Another similar file format is PPTM which differs in opening with Microsoft PowerPoint in editable format instead of running as Slide Show. When run as slide show, the PPSM file shows the presentation slides with contents intact in the slide show and is in read-only mode by default. PPSM files can still be edited in Microsoft PowerPoint by opening it in PowerPoint.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, ODP'yi aşağıda listelenen birkaçı dahil olmak üzere diğer birçok dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-html/" name="ODP TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pdf/" name="ODP TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-png/" name="ODP TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Açık XML sunum Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-svg/" name="ODP TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/java/conversion/odp-to-xps/" name="ODP TO XPS" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}