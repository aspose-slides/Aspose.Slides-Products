---
title: A PPSX-fájlok metaadatainak megtekintése vagy szerkesztése .NET-en keresztül
weight: 1570
url: /hu/net/metadata/ppsx/ 
description: C# forráskód a PPSX formátumú metaadatok szerkesztéséhez vagy megtekintéséhez .NET Framework, .NET Core, Windows Azure, Mono vagy Xamarin platformokon.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPSX metaadatok kibontása .NET-en keresztül" h2="Készítse el saját .NET-alkalmazásait a PPSX-fájlok metaadatainak hozzáadásához, szerkesztéséhez, eltávolításához vagy kibontásához szerveroldali API-k segítségével." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PPSX metaadatok kinyerése C# használatával" %}}

 A PPSX metaadatok kinyeréséhez ezt használjuk
 [Aspose.Slides for .NET](https://products.aspose.com/slides/hu/net)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentum-metaadat API C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 csomagkezelő, keressen
 **Aspose.Slides**
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="A PPSX metaadatainak C#-on keresztüli kibontásának lépései" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Az IDocumentProperties osztály a bemutatófájlhoz társított dokumentumtulajdonságokat képviseli. A fejlesztők ezt a tulajdonságot használhatják a metaadatok eléréséhez az alábbiak szerint." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Példányosítsa a Presentation osztályt a PPSX fájl elérési útjával
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
A bemutatóhoz társított DocumentProperties objektum lekérése
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ugorjon át a DocumentProperties objektum elemei között
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Egyéni tulajdonságok elérése és módosítása
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Az Aspose.Slides for .NET minden nagyobb operációs rendszeren támogatott. Csak győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal.
- Fejlesztői környezet, mint a Microsoft Visual Studio.
- A projektben hivatkozott Aspose.Slides for .NET.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSX metaadatainak kibontása - C#" offSpacer="" %}}

```cs

// instantiate the Presentation class with path to PPSX file
var presentation = new Aspose.Slides.Presentation("template.ppsx");

// get DocumentProperties object associated with the Presentation object
var properties = presentation.DocumentProperties;

// access and modify custom properties
for (int i = 0; i < properties.CountOfCustomProperties; i++)
{
    // display names and values of custom properties
    System.Console.WriteLine("Custom Property Name : " + properties.GetCustomPropertyName(i));
    System.Console.WriteLine("Custom Property Value : " + properties[properties.GetCustomPropertyName(i)]);

    // modify values of custom properties
    properties[properties.GetCustomPropertyName(i)] = "New Value " + (i + 1);
}

// save your presentation to a file
presentation.Save("output.ppsx", Aspose.Slides.Export.SaveFormat.Ppsx);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Az Aspose.Slides for .NET API-ról" %}}

 Az Aspose.Slides API használható Microsoft PowerPoint dokumentumok olvasására, írására, manipulálására és konvertálására PDF, XPS, HTML, TIFF, ODP és számos más formátumba. Új fájlokat lehet létrehozni a semmiből, és elmenteni azokat a megfelelő támogatott formátumokba. Az Aspose.Slides egy önálló API prezentációk, diák és elemek létrehozására, elemzésére vagy manipulálására, és nem függ semmilyen szoftvertől, például a Microsofttól vagy az OpenOffice-tól.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of PPSX via Online App" sectionDescription="View & edit Metadata to PPSX documents by using our [Live Demos](https://products.aspose.app/slides/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your PPSX file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" >}}
PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott metaadat-formátumok" subTitle="A C# használatával sok más formátum metaadatait is lehet manipulálni, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/odp/" name="ODP" description="OpenDocument prezentációs formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/otp/" name="OTP" description="OpenDocument szabványos formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/pot/" name="POT" description="Microsoft PowerPoint sablonfájlok" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/potm/" name="POTM" description="Microsoft PowerPoint sablonfájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/potx/" name="POTX" description="Microsoft PowerPoint sablon bemutató" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/pps/" name="PPS" description="PowerPoint diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/ppsm/" name="PPSM" description="Makró-képes diavetítés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/pptm/" name="PPTM" description="Makró-kompatibilis prezentációs fájl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/net/metadata/pptx/" name="PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}