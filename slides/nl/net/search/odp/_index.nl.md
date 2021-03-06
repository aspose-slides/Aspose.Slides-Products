---
title: Zoek ODP-document zonder te openen via C#
weight: 8110
url: /nl/net/search/odp/ 
description: C#-broncode om woorden met patroon in ODP-bestand te zoeken op .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Zoek ODP-indelingen in C #" h2="Native en high-performance ODP-document zoeken met Aspose.Slides aan de serverzijde voor .NET API's, zonder het gebruik van software zoals Microsoft of Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe ODP-bestand te zoeken met behulp van C #" %}}

 Om het ODP-bestand te doorzoeken, gebruiken we
 [Aspose.Slides voor .NET](https://products.aspose.com/slides/nl/net)
 API, een veelzijdige, krachtige en gebruiksvriendelijke zoek-API voor PowerPoint-presentaties voor het C#-platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakketbeheerder, zoek naar Aspose.Slides en installeer. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheer Console-opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Stappen om ODP-bestanden te zoeken in C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Een eenvoudige documentzoekopdracht met [Aspose.Slides for .NET](https://products.aspose.com/slides/nl/net) API's kan worden gedaan met slechts enkele regels code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP-bestand.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Krijg alle tekstvakken in presentatie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Zoek de tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Vervang de tekst.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Schrijf de ODP-presentatie.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/agp/feature-section-col >}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Onze API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat u de volgende vereisten op uw systeem hebt.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Windows Azure, Mono of Xamarin Platforms
- Ontwikkelomgeving zoals Microsoft Visual Studio
- Aspose.Slides voor .NET DLL waarnaar in uw project wordt verwezen - Installeer vanaf NuGet met behulp van de downloadknop hierboven

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Zoek ODP-bestanden - C#" offSpacer="" %}}

```cs
Presentation pres = new Presentation("filetobesearched.odp");

//Get all text boxes in the presentation

ITextFrame[] tb = SlideUtil.GetAllTextBoxes(pres.Slides[0]);

for (int i = 0; i < tb.Length; i++)

foreach (Paragraph para in tb[i].Paragraphs)

    foreach (Portion port in para.Portions)

        //Search text to be replaced

        if (port.Text.Contains(strToFind))

        //Replace exisitng text with the new text

        {

            string str = port.Text;

            int idx = str.IndexOf(strToFind);

            string strStartText = str.Substring(0, idx);

            string strEndText = str.Substring(idx + strToFind.Length, str.Length - 1 - (idx + strToFind.Length - 1));

            port.Text = strStartText + strToReplaceWith + strEndText;

        }

pres.Save("filetobesearched.odp",Aspose.Slides.Export.SaveFormat.Odp);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

 Slides API kan worden gebruikt om Microsoft PowerPoint-documenten te lezen, schrijven, manipuleren en converteren naar PDF, XPS, HTML, TIFF, ODP en verschillende andere formaten. Men kan vanaf het begin nieuwe bestanden maken en deze opslaan in de relevante ondersteunde formaten. Aspose.Slides is een zelfstandige API voor het maken, parseren of manipuleren van presentaties, dia's en elementen en is niet afhankelijk van software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Search Live Demos" sectionDescription="Search text, words, phrases within ODP documents right now by visiting our [Live Demos website](https://products.aspose.app/slides/search). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your ODP files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ODP " readMoreLink="https://docs.fileformat.com/presentation/odp/" >}}
Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. A presentation file is a collection of slides where each slide can comprise of text, images, formatting, animations, and other media. These slides are presented to audience in the form of slideshows with custom presentation settings. ODP files can be opened by applications that conform to the OpenDocument format (such as OpenOffice or StarOffice). 

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekformaten" subTitle="Met C# kan men ook in andere formaten zoeken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/search/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/search/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}