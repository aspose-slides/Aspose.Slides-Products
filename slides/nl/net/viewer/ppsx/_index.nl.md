---
title: Bekijk PPSX-bestandsindelingen via .NET
weight: 2370
url: /nl/net/viewer/ppsx/ 
description: C#-broncode voor het laden, weergeven en weergeven van PPSX-documenten op .NET Framework-, .NET Core-, Windows Azure-, Mono- of Xamarin-platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="PPSX-bestandsviewer voor .NET" h2="Bekijk presentatiebestanden zoals PPSX zonder Microsoft PowerPoint of Office Automation" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PPSX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-slides" liveDemosLink="https://products.aspose.app/slides/family" docsLink="https://docs.aspose.com/slides/net" installationsDocsLink="https://docs.aspose.com/slides/net" nugetLink="https://www.nuget.org/packages/aspose.slides.net" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/slides/net" learnAsLink="https://docs.aspose.com/slides/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hoe PPSX-bestand te bekijken met C #" %}}

 Om het PPSX-bestand te bekijken, gebruiken we
 [Aspose.Slides voor .NET](https://products.aspose.com/slides/nl/net)
 API, een veelzijdige, krachtige en gebruiksvriendelijke API voor het C#-platform die met elke viewer kan worden gebruikt. Open
 [NuGet](https://www.nuget.org/packages/aspose.slides.net)
 pakketbeheerder, zoek naar
 **Aspose.Dia's**
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheer Console-opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Slides.NET

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}


{{< blocks/products/pf/agp/feature-section-col title="Stappen om PPSX via C# te bekijken" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Aspose.Slides maakt het de ontwikkelaars gemakkelijk om het PPSX-bestand te bekijken met slechts enkele regels code." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instantieer een presentatie-object en laad het PPSX-bestand
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van ResponsiveHtmlController voor opmaak
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Maak een instantie van HtmlOptions en stel de eigenschap HtmlFormatter in
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla de PPSX-presentatie op in HTML-indeling
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Roep Process.Start aan met pad naar resulterende HTML om PPSX-inhoud in standaardbrowser te laden
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

{{% blocks/products/pf/agp/code-block title="C# voorbeeldcode om het PPSX-bestand te bekijken" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// instantiate a Presentation object & load the PPSX file
using (var presentation = new Aspose.Slides.Presentation("templateppsx"))
{
    // create HTML export controller
    var controller = new Aspose.Slides.Export.ResponsiveHtmlController();
    // create an instance of HtmlOptions and set HtmlFormatter property
    var htmlOptions = new Aspose.Slides.Export.HtmlOptions 
    { 
        HtmlFormatter = Aspose.Slides.Export.HtmlFormatter.CreateCustomFormatter(controller) 
    };

    // save the presentation in HTML
    presentation.Save(output, Aspose.Slides.Export.SaveFormat.Html, htmlOptions);
}
// load HTML to view the presentation content
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.Slides voor .NET API" %}}

 Aspose.Slides API kan worden gebruikt om Microsoft PowerPoint-documenten te lezen, schrijven, manipuleren en converteren naar PDF, XPS, HTML, TIFF, ODP en verschillende andere formaten. Men kan vanaf het begin nieuwe bestanden maken en deze opslaan in de relevante ondersteunde formaten. Aspose.Slides is een zelfstandige API voor het maken, parseren of manipuleren van presentaties, dia's en elementen en is niet afhankelijk van software zoals Microsoft of OpenOffice.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View PPSX" sectionDescription="Check our live demos to [View PPSX](https://products.aspose.app/slides/viewer/ppsx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PPSX file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download PPSX file from the link, if required" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PPSX" readMoreLink="https://docs.fileformat.com/presentation/ppsx/" >}}
PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. It is an update to the PPS file format that was supported by Microsoft PowerPoint 97-2003 versions. When a PPSX file is shared with another user and opened, it starts as PowerPoint show unlike PPTX file that opens in editable mode. The sequence of slide show is the same as in the original presentation. All the slides accompany the images, sounds and other embedded media accompany the presentation slides to the PPSX during the slideshow.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde viewerformaten" subTitle="Met behulp van C # kan men ook vele andere bestandsindelingen bekijken, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/odp/" name="ODP" description="OpenDocument-presentatie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/otp/" name="OTP" description="Standaardformaat OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/pot/" name="POT" description="Microsoft PowerPoint-sjabloonbestanden" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/potm/" name="POTM" description="Microsoft PowerPoint-sjabloonbestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/potx/" name="POTX" description="Microsoft PowerPoint-sjabloonpresentatie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/pps/" name="PPS" description="PowerPoint-diavoorstelling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/ppsm/" name="PPSM" description="Diavoorstelling met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/pptm/" name="PPTM" description="Presentatiebestand met macro's" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/viewer/pptx/" name="PPTX" description="Open XML-presentatie-indeling" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}