---
title: C++ uygulaması aracılığıyla EMF'yi GIF'e dönüştürün
weight: 8530
url: /tr/cpp/conversion/emf-to-gif/ 
description: EMF belgesi için GIF formatına örnek C++ dönüştürme kodu. Herhangi bir C++ Uygulamasında toplu EMF'den GIF'e dönüştürme için örnek kod kullanın.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="EMF'yi C++ ile GIF'e dönüştürün" h2="Microsoft PowerPoint kurulumuna ihtiyaç duymadan C++ kitaplığını kullanarak yüksek performanslı EMF'den GIF'e dönüştürme." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C++ Kullanarak EMF'yi GIF'e Dönüştürme" %}}

 EMF'yi GIF'e dönüştürmek için kullanacağız
 [Aspose.Slides for C++](https://products.aspose.com/slides/tr/cpp)
 C++ platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API'si olan API. En son sürümünü doğrudan indirebilirsiniz, sadece açın
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 paket yöneticisi, ara
 Aspose.Slides.Cpp
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Emretmek" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="EMF'yi C++ ile GIF'e Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 C++ geliştiricileri, yalnızca birkaç satır kodla EMF dosyasını GIF'e kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. EMF dosyasını Aspose.Slides for C++ Presentation Object ile yükleyin.
1. İlk slaydı seçin.
1. İstenen boyutları ayarlayın.
1. Küçük resmi istediğiniz boyutlarda alın.
1. GIF çıktı parametresine sahip Save() yöntemini çağırın.
1. GIF dosyasını uyumlu programda açın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 C++ dönüştürme örnek kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya Windows 32 bit, Windows 64 bit ve Linux 64 bit için C++ Runtime Environment ile uyumlu bir işletim sistemi.
- Projenizde referans verilen C++ DLL için Aspose.Slides.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="EMF'den GIF'e C++ Dönüştürme Kaynak Kodu" offSpacer="" %}}

```cs
// Load the EMF
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.emf");

// Access the first slide
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// User defined dimension
int desiredX = 1200;
int desiredY = 800;

// Getting scaled value  of X and Y
float ScaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float ScaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

// Create a custom scale image
auto bitmap = slide->GetThumbnail(ScaleX, ScaleY);

bitmap->Save(u"output.gif", ImageFormat::get_Gif());
	
//Iterate through each slide via index and convert

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension="emf-to-gif"
        sectionTitle="EMF 'a dönüştürmek için ücretsiz uygulama GIF" 
        sectionDescription="[Ücretsiz Editor uygulamamızı deneyin](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, EMF'yi aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere diğer birçok dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-bmp/" name="EMF TO BMP" description="Bitmap Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-html/" name="EMF TO HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-jpeg/" name="EMF TO JPEG" description="JPEG Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-odp/" name="EMF TO ODP" description="OpenDocument Sunum Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-otp/" name="EMF TO OTP" description="OpenDocument Standart Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-pdf/" name="EMF TO PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-png/" name="EMF TO PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-pot/" name="EMF TO POT" description="Microsoft PowerPoint Şablon Dosyaları" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-potm/" name="EMF TO POTM" description="Microsoft PowerPoint Şablon Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-potx/" name="EMF TO POTX" description="Microsoft PowerPoint Şablonu Sunumu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-pps/" name="EMF TO PPS" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-ppsm/" name="EMF TO PPSM" description="Makro Etkin Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-ppsx/" name="EMF TO PPSX" description="PowerPoint Slayt Gösterisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-ppt/" name="EMF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-pptm/" name="EMF TO PPTM" description="Makro Etkin Sunum Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-pptx/" name="EMF TO PPTX" description="Açık XML sunum Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-svg/" name="EMF TO SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-tiff/" name="EMF TO TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-xml/" name="EMF TO XML" description="Genişletilebilir İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/tr/cpp/conversion/emf-to-xps/" name="EMF TO XPS" description="XML Kağıt Özellikleri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}