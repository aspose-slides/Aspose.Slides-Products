---
title: Java aracılığıyla ODP belgesinin kilidini açın
weight: 3650
url: /tr/java/unlock/odp/ 
description: JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment'da parola korumalı ODP dosyasının kilidini açmak için Java örnek kodu.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Java ile ODP Dosyalarının Kilidini Açın" h2="Java Kitaplığı kullanarak ODP dosyası dahil olmak üzere PowerPoint sunumlarından korumayı kaldırın." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/java" installationsDocsLink="https://docs.aspose.com/slides/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/java" learnAsLink="https://docs.aspose.com/slides/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-slides" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak Koruma ODP Dosyası Nasıl Kaldırılır" %}}

 ODP dosyasının kilidini açmak için kullanacağız
 [Aspose.Slides for Java](https://products.aspose.com/slides/tr/java)
 Java platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir koruma API'si olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
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


{{< blocks/products/pf/agp/feature-section-col title="Java aracılığıyla ODP'nin kilidini açma adımları" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kilitli ODP'yi bir Sunum örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
isWriteProtected boolean type özelliğini kullanarak korumayı kontrol edin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
RemoveWriteProtection() yöntemini kullanarak korumayı kaldırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sonucu ODP formatında kaydet
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides for Java, tüm büyük platformlarda ve İşletim Sistemlerinde destekler. Lütfen aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# ile ODP Dosyalarının Kilidini Açın" offSpacer="" %}}

```cs

// Open the ODP file
Presentation pres = new Presentation("WriteProtectedFile.odp");

// Checking if presentation is write protected
if (pres.getProtectionManager().isWriteProtected())
	// Removing Write protection
	pres.getProtectionManager().removeWriteProtection();

// Saving presentation
pres.save("output.odp", com.aspose.slides.SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Slides for Java API hakkında" %}}

 Aspose.Slides API, Microsoft PowerPoint belgelerini okumak, yazmak, değiştirmek ve PDF, XPS, HTML, TIFF, ODP ve diğer çeşitli formatlara dönüştürmek için kullanılabilir. Sıfırdan yeni dosyalar oluşturabilir ve bunları ilgili desteklenen biçimlerde kaydedebilirsiniz. Aspose.Slides, sunumlar, slaytlar ve öğeler oluşturmak, ayrıştırmak veya değiştirmek için bağımsız bir API'dir ve Microsoft veya OpenOffice gibi herhangi bir yazılıma bağlı değildir.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Unlock ODP" sectionDescription="Check our live demos to [unlock ODP files](https://products.aspose.app/slides/unlock/odp) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Kilit Açma Formatları" subTitle="Java kullanarak, dahil olmak üzere farklı biçimlerin korumasını / kilidinin açılmasını kolayca kaldırabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/unlock/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/java/unlock/pptx/" name="PPTX" description="Açık XML sunum Formatı" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}