---
title: Převeďte TIFF na PPSM pomocí aplikace C++
weight: 4800
url: /cs/cpp/conversion/tiff-to-ppsm/ 
description: Ukázka převodního kódu C++ pro dokument TIFF do formátu PPSM. Použijte ukázkový kód pro dávkový převod TIFF na PPSM v jakékoli aplikaci C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převeďte TIFF na PPSM přes C++" h2="Vysoce výkonný převod TIFF na PPSM pomocí knihovny C++ bez nutnosti instalace Microsoft PowerPoint." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSM" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="TIFF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp" installationsDocsLink="https://docs.aspose.com/slides/cpp" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést TIFF na PPSM pomocí C++" %}}

 Abychom převedli TIFF na PPSM, použijeme
 [Aspose.Slides pro C++](https://products.aspose.com/slides/cs/cpp)
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu TIFF na PPSM přes C++" %}}

{{% blocks/products/pf/agp/text %}}

 Vývojáři C++ mohou snadno převést soubor TIFF na PPSM pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načtěte soubor TIFF pomocí Aspose.Slides pro C++ Presentation Object.
1. Zavolejte metodu Save().
1. Předejte cestu k výstupnímu souboru s příponou (PPSM).
1. Soubor PPSM bude uložen do zadané cesty.
1. Otevřete soubor PPSM v kompatibilním programu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového kódu převodu C++ se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s C++ Runtime Environment pro Windows 32 bit, Windows 64 bit a Linux 64 bit.
- Aspose.Slides pro C++ DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zdrojový kód konverze TIFF na PPSM C++" offSpacer="" %}}

```cs
// Load the TIFF.
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"sourceFile.tiff");
// Save in PPSM format.
prs->Save(u"convertedFile.ppsm", Aspose::Slides::Export::SaveFormat::Ppsm);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

<!-- aboutfile Ends -->

    {{< blocks/slides-app-widget 
        appName="conversion"
        extension=""
        sectionTitle="Aplikace zdarma k převodu TIFF na PPSM" 
        sectionDescription="[Vyzkoušejte zdarma Editor App](https://products.aspose.app/slides/editor/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Můžete také převést TIFF do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-bmp/" name="TIFF TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-emf/" name="TIFF TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-gif/" name="TIFF TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-html/" name="TIFF TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-jpeg/" name="TIFF TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-odp/" name="TIFF TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-otp/" name="TIFF TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pdf/" name="TIFF TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-png/" name="TIFF TO PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pot/" name="TIFF TO POT" description="Soubory šablon Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-potm/" name="TIFF TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-potx/" name="TIFF TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pps/" name="TIFF TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-ppsx/" name="TIFF TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-ppt/" name="TIFF TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pptm/" name="TIFF TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-pptx/" name="TIFF TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-svg/" name="TIFF TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-xml/" name="TIFF TO XML" description="Rozšiřitelný značkovací jazyk" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/cs/cpp/conversion/tiff-to-xps/" name="TIFF TO XPS" description="Specifikace papíru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}