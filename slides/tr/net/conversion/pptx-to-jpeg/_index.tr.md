---
title: PPTX'i C# ile JPEG'e dönüştürün
weight: 480
url: /tr/net/conversion/pptx-to-jpeg/ 
description: PPTX'ten JPEG C#'a dönüştürme için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu PPTX dosyalarını JPEG dönüştürme için API örnek kodunu kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPTX'i C# ile JPEG'e dönüştürün" h2="PowerPoint® PPTX dosyalarını .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında JPEG olarak dışa aktarın" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak PPTX'i JPEG'e Dönüştürme" %}}

 PPTX'i JPEG'e dönüştürmek için kullanacağız
 [Aspose.Slides for .NET](https://products.aspose.com/slides/tr/net)
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API'si olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 paket yöneticisi, ara
 Aspose.Slides
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="PPTX'i C# ile JPEG'e Dönüştürme Adımları" >}}

{{< blocks/products/pf/agp/steps-block-autogen name=".NET geliştiricileri, PPTX dosyalarını yalnızca birkaç satır kodla kolayca yükleyebilir ve JPEG'e dönüştürebilir." >}}

{{< blocks/products/pf/agp/step-autogen >}}
PPTX dosyasını bir Presentation sınıfı örneğiyle yükleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sunumdaki her Slaytı yineleyin
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Her yinelemede Bitmap olarak tam ölçekli bir görüntü oluşturun
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Parametre olarak JPEG dosya uzantısı ve ImageFormat.Jpeg ile Bitmap.Save yöntemini çağırın
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme örnek kaynak kodunu çalıştırmadan önce aşağıdaki önkoşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi.
- Microsoft Visual Studio gibi geliştirme ortamı.
- Projenizde referans verilen .NET DLL için Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, PPTX'ten JPEG'e C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pptx"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in JPEG format
        bitmap.Save(string.Format("Slide_{0}.jpeg", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
    }
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="PPTX 'a dönüştürmek için ücretsiz uygulama JPEG" 
        sectionDescription="[PPT için JPG dönüştürmek için ücretsiz uygulamamızı deneyin.](https://products.aspose.app/slides/conversion/ppt-to-jpg)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca PPTX'i aşağıda listelenen birkaç dosya formatı da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-emf/" name="PPTX TO EMF" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-gif/" name="PPTX TO GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-html/" name="PPTX TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-odp/" name="PPTX TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-otp/" name="PPTX TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-pdf/" name="PPTX TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-png/" name="PPTX TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-pot/" name="PPTX TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-potm/" name="PPTX TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-potx/" name="PPTX TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-pps/" name="PPTX TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-ppsm/" name="PPTX TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-ppsx/" name="PPTX TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-ppt/" name="PPTX TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-pptm/" name="PPTX TO PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-svg/" name="PPTX TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-swf/" name="PPTX TO SWF" description="SWF Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-tiff/" name="PPTX TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/net/conversion/pptx-to-xps/" name="PPTX TO XPS" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}