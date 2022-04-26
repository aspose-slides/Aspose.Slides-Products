---
title: Ontgrendel ODP-document via .NET
weight: 5780
url: /nl/net/unlock/odp/ 
description: C#-broncode om met een wachtwoord beveiligd ODP-bestand te ontgrendelen op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Ontgrendel ODP-presentatie via C #" h2="Verwijder de bescherming van ODP met behulp van de .NET-bibliotheek." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe een ODP-bestand te ontgrendelen met C #" %}}

 Om het beschermings-ODP-bestand te verwijderen, gebruiken we
 [Aspose.Slides voor .NET](https://products.aspose.com/slides/net)
 API, een veelzijdige, krachtige en gebruiksvriendelijke API voor documentbeveiliging voor het C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakketbeheerder, zoek naar
 **Aspose.Dia's**
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.Dia's" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Ontgrendel ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="U hebt [aspose.slides.dll](https://downloads.aspose.com/slides/net) nodig waarnaar in uw project wordt verwezen om de volgende workflow uit te voeren." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad vergrendelde ODP met een exemplaar van Presentation
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Controleer de beveiliging met behulp van IProtectionManager.IsWriteProtected boolean type eigenschap
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwijder de bescherming met behulp van de IProtectionManager.RemoveWriteProtection-methode
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Resultaat opslaan in ODP-formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Slides voor .NET wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms
- Ontwikkelomgeving zoals Microsoft Visual Studio
- Aspose.Slides voor .NET waarnaar in uw project wordt verwezen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Opdracht" offSpacer="" %}}

```cs

// load locked ODP file
var presentation = new Slides.Presentation("locked.odp");

// check if presentation is write protected
if (presentation.ProtectionManager.IsWriteProtected)
    // remove protection                
    presentation.ProtectionManager.RemoveWriteProtection();

// save presentation
presentation.Save("output.ppt", Aspose.Slides.Export.SaveFormat.Odp);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Slides voor .NET API" %}}

 Aspose.Slides API kan worden gebruikt om Microsoft PowerPoint-documenten te lezen, schrijven, manipuleren en converteren naar PDF, XPS, HTML, TIFF, ODP en verschillende andere formaten. Men kan vanaf het begin nieuwe bestanden maken en deze opslaan in de relevante ondersteunde formaten. Aspose.Slides is een zelfstandige API voor het maken, parseren of manipuleren van presentaties, dia's en elementen en is niet afhankelijk van software zoals Microsoft of OpenOffice.  



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

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde ontgrendelingsformaten" subTitle="Met behulp van C # kan men gemakkelijk de bescherming / ontgrendeling van verschillende formaten verwijderen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/unlock/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/net/unlock/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}