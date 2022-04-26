---
title: ODP konvertálása SVG-vé a C# segítségével
weight: 5990
url: /hu/net/conversion/odp-to-svg/ 
description: Mintakód az ODP-SVG C# konverzióhoz. Használjon API-példakódot az ODP-fájlok kötegelt konvertálásához SVG-vé VB.NET-en, Asp.NET-en vagy bármely .NET-alapú alkalmazáson belül.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="ODP konvertálása SVG-vé a C# segítségével" h2="Exportáljon PowerPoint® ODP fájlokat SVG-be .NET-keretrendszeren, .NET Core-on, Windows Azure-on, Mono- vagy Xamarin-platformokon" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hogyan lehet az ODP-t SVG-vé konvertálni C# használatával" %}}

 Az ODP SVG-vé konvertálásához használjuk
 [Aspose.Slides for .NET](https://products.aspose.com/slides/net)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 csomagkezelő, keressen
 Aspose.Diák
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Az ODP SVG-vé konvertálásának lépései C# segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="A .NET-fejlesztők egyszerűen, néhány sornyi kóddal tölthetik be és konvertálhatják az ODP fájlokat SVG formátumba." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Töltse be az ODP-fájlt a Prezentáció osztály példányával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Hívja meg a Mentés metódust, miközben paraméterként adja meg a kimeneti fájl elérési útját és a SaveFormat.Svg-t
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Az SVG fájl a megadott elérési útra kerül mentésre
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós mintaforráskód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal.
- Fejlesztői környezet, mint a Microsoft Visual Studio.
- Aspose.Slides for .NET DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód az ODP-ből SVG C# konvertálást mutat be" offSpacer="" %}}

```cs
using (Presentation pres = new Presentation("template.odp"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];

        using (FileStream fileStream = new FileStream($"slide-{index}.svg", FileMode.Create, FileAccess.Write))
        {
            slide.WriteAsSvg(fileStream);   
        }
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
        extension="odp-to-svg"
        sectionTitle="Ingyenes alkalmazás a ODP konvertálásához SVG -re" 
        sectionDescription="[Próbálja ki az ingyenes Collage alkalmazást](https://products.aspose.app/slides/collage/)" 
    >}}
    
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Az ODP-t sok más fájlformátumra is konvertálhatja, beleértve az alábbiakban felsorolt ​​néhányat." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-bmp/" name="ODP TO BMP" description="Bittérképes kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-emf/" name="ODP TO EMF" description="Továbbfejlesztett metafájl formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-gif/" name="ODP TO GIF" description="Grafikus csereformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-html/" name="ODP TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-jpeg/" name="ODP TO JPEG" description="JPEG kép" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-otp/" name="ODP TO OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pdf/" name="ODP TO PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-png/" name="ODP TO PNG" description="Hordozható hálózati grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pot/" name="ODP TO POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-potm/" name="ODP TO POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-potx/" name="ODP TO POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pps/" name="ODP TO PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppsm/" name="ODP TO PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppsx/" name="ODP TO PPSX" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-ppt/" name="ODP TO PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pptm/" name="ODP TO PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-pptx/" name="ODP TO PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-swf/" name="ODP TO SWF" description="SWF formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-tiff/" name="ODP TO TIFF" description="Címkézett képformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/conversion/odp-to-xps/" name="ODP TO XPS" description="XML papírspecifikációk" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}