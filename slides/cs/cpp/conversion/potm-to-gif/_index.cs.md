---
title: Převeďte POTM na GIF pomocí aplikace C++
weight: 1350
url: /cs/cpp/conversion/potm-to-gif/ 
description: Ukázka převodního kódu C++ pro dokument POTM do formátu GIF. Použijte ukázkový kód pro dávkovou konverzi POTM na GIF v jakékoli aplikaci C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převeďte POTM na GIF přes C++" h2="Vysoce výkonný převod POTM na GIF pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést POTM na GIF pomocí C++" %}}

 Abychom převedli POTM na GIF, použijeme
 [Aspose.Slides pro C++](https://products.aspose.com/slides/cpp/)
 API, což je funkčně bohaté, výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi dokumentů pro platformu C++. Jeho nejnovější verzi si můžete stáhnout přímo, stačí otevřít
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 správce balíčků, vyhledejte
 Aspose.Slides.Cpp
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu POTM na GIF přes C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři C++ mohou snadno převést soubor POTM na GIF v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor POTM pomocí Aspose.Slides pro C++ Presentation Object.
1. Vyberte první snímek.
1. Nastavte požadované rozměry.
1. Získejte miniaturu s požadovanými rozměry.
1. Zavolejte metodu Save() s výstupním parametrem GIF.
1. Otevřete soubor GIF v kompatibilním programu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu převodu C++ se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
- Aspose.Slides pro C++ DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze POTM na GIF C++" offSpacer="" %}}

```cs
// Load the POTM
SharedPtr<Presentation> pres = MakeObject<Presentation>(u"sourceFile.potm");

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
        extension=""
        sectionTitle="Aplikace zdarma k převodu POTM na GIF" 
        sectionDescription="[Vyzkoušejte zdarma Text To Gif App](https://products.aspose.app/slides/text-to-gif/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést POTM do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-bmp/" name="POTM TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-emf/" name="POTM TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-html/" name="POTM TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-jpeg/" name="POTM TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-odp/" name="POTM TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-otp/" name="POTM TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-pdf/" name="POTM TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-png/" name="POTM TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-pot/" name="POTM TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-potx/" name="POTM TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-pps/" name="POTM TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppsm/" name="POTM TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppsx/" name="POTM TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-ppt/" name="POTM TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-pptm/" name="POTM TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-pptx/" name="POTM TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-svg/" name="POTM TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-tiff/" name="POTM TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-xml/" name="POTM TO XML" description="Rozšiřitelný značkovací jazyk" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cpp/conversion/potm-to-xps/" name="POTM TO XPS" description="Specifikace papíru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}