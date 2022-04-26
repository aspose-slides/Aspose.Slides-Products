---
title: Převést POT na PNG přes C#
weight: 6430
url: /cs/net/conversion/pot-to-png/ 
description: Ukázkový kód pro převod POT do PNG C#. Použijte ukázkový kód API pro dávkový převod souborů POT do PNG v rámci VB.NET, Asp.NET nebo jakékoli aplikace založené na .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést POT na PNG přes C#" h2="Export souborů PowerPoint® POT do PNG na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést POT na PNG pomocí C#" %}}

 K převodu POT na PNG použijeme
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API, což je funkčně bohaté, výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi dokumentů pro platformu C#. OTEVŘENO
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 správce balíčků, vyhledejte
 Aspose.Slides
 a nainstalovat. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Kroky k převodu POT na PNG přes C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Vývojáři .NET mohou snadno načíst a převést soubory POT do PNG v několika řádcích kódu." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Načtěte soubor POT s instancí třídy Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterujte každý snímek v prezentaci
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vytvořte obraz v plném měřítku jako bitmapu s každou iterací
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Volejte metodu Bitmap.Save s příponou souboru PNG & ImageFormat.Png jako parametry
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním ukázkového zdrojového kódu převodu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Slides pro .NET DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento ukázkový kód ukazuje převod POT do PNG C#" offSpacer="" %}}

```cs
using (var presentation = new Presentation("template.pot"))
{
    // iterate over all slides in the presentation
    foreach (var slide in presentation.Slides)
    {
        // create a full scale image
        var bitmap = slide.GetThumbnail(1f, 1f);

        // save the image to disk in PNG format
        bitmap.Save(string.Format("Slide_{0}.png", slide.SlideNumber), System.Drawing.Imaging.ImageFormat.Png);
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
        extension="pot-to-png"
        sectionTitle="Aplikace zdarma k převodu POT na PNG" 
        sectionDescription="[Vyzkoušejte naši bezplatnou aplikaci pro převod PPT až PNG](https://products.aspose.app/slides/conversion/ppt-to-png)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="POT můžete také převést do mnoha dalších formátů souborů, včetně několika níže uvedených." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-bmp/" name="POT TO BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-emf/" name="POT TO EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-gif/" name="POT TO GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-html/" name="POT TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-jpeg/" name="POT TO JPEG" description="Obrázek JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-odp/" name="POT TO ODP" description="Formát prezentace OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-otp/" name="POT TO OTP" description="Standardní formát OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pdf/" name="POT TO PDF" description="Přenosný formát dokumentu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-potm/" name="POT TO POTM" description="Soubor šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-potx/" name="POT TO POTX" description="Prezentace šablony Microsoft PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pps/" name="POT TO PPS" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppsm/" name="POT TO PPSM" description="Prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppsx/" name="POT TO PPSX" description="Prezentace PowerPoint" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-ppt/" name="POT TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pptm/" name="POT TO PPTM" description="Soubor prezentace s podporou maker" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-pptx/" name="POT TO PPTX" description="Formát otevřené prezentace XML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-svg/" name="POT TO SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-swf/" name="POT TO SWF" description="Formát SWF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-tiff/" name="POT TO TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/pot-to-xps/" name="POT TO XPS" description="Specifikace papíru XML" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}