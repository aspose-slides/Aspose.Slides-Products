---
title: Az ODP-dokumentumok védelme és zárolása C++-on keresztül
weight: 670
url: /hu/cpp/protect/odp/ 
description: C++ példakód az ODP-fájl zárolására jelszóval a C++ Runtime Environment for Windows 32 bites, a Windows 64 bites és a Linux 64 bites rendszeren.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="ODP fájlok titkosítása C++ segítségével" h2="Jelszóval védheti a PowerPoint prezentációkat, beleértve az ODP formátumot is a .NET Library használatával." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/cpp/" installationsDocsLink="https://docs.aspose.com/slides/cpp/" nugetLink="https://www.nuget.org/packages/aspose.slides" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/cpp" learnAsLink="https://docs.aspose.com/slides/cpp/" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Az ODP-fájlok biztonságossá tétele C++ használatával" %}}

 Az ODP-fájl védelme érdekében használjuk
 [Aspose.Slides for C++](https://products.aspose.com/slides/hu/cpp)
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumtitkosító API C++ platformhoz. A legújabb verziót közvetlenül letöltheti, csak nyissa meg
 [NuGet](https://www.nuget.org/packages/aspose.slides)
 csomagkezelő, keressen
 **Aspose.Slides.Cpp**
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Aspose.Diák" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Az ODP-fájlok védelmének lépései C++ segítségével" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="A dokumentumvédelem az Aspose.Slides API-kkal néhány sornyi kóddal elvégezhető." >}}

{{< blocks/products/pf/agp/step-autogen >}}
ODP fájl betöltése
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Állítsa be a jelszót a get\_ProtectionManager()->Encrypt(.) metódussal
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Védett ODP-prezentáció mentése
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 Az Aspose.Slides for C++ támogatja az összes főbb platformon és operációs rendszeren. Kérjük, győződjön meg arról, hogy rendelkezik az alábbi előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer C++ futási környezettel Windows 32 bites, Windows 64 bites és Linux 64 bites rendszerhez.
- Aspose.Slides for C++ DLL, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Parancs" offSpacer="" %}}

```cs

const String sourceFilePath = u"SourcePath\SourceFile.odp";
const String outputFilePath = u"OutputPath\OutPutFile.odp";

// Load the ODP file
SharedPtr<Presentation> odpFile = MakeObject<Presentation>(sourceFilePath);

// Protect with password
odpFile->get_ProtectionManager()->Encrypt(u"password");

// Save the ODP
odpFile->Save(outputFilePath, SaveFormat::Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="Az Aspose.Slides for C++ API-ról" %}}

 Az Aspose.Slides API használható Microsoft PowerPoint dokumentumok olvasására, írására, manipulálására és konvertálására PDF, XPS, HTML, TIFF, ODP és számos más formátumba. Új fájlokat lehet létrehozni a semmiből, és elmenteni azokat a megfelelő támogatott formátumokba. Az Aspose.Slides egy önálló API prezentációk, diák és elemek létrehozására, elemzésére vagy manipulálására, és nem függ semmilyen szoftvertől, például a Microsofttól vagy az OpenOffice-tól.  



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect ODP" sectionDescription="Check our live demos to [encrypt ODP files](https://products.aspose.app/slides/protect/odp) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload ODP file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant ODP file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP" readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice).

    {{< /blocks/products/pf/agp/i18n/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott védelmi dokumentumok" subTitle="A C++ használatával más fájlokat is védhet, beleértve." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/protect/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hu/cpp/protect/pptx/" name="PPTX" description="Nyissa meg az XML prezentációs formátumot" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}