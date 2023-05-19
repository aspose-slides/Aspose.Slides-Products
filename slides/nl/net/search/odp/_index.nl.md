---
title: Zoek tekst in ODP presentatiebestanden met behulp van .NET
url: /nl/net/search/odp/
keywords: zoek woorden in ODP, zoek en vervang tekst in ODP, zoek tekst ODP Presentatie
description: C# broncode om tekst te zoeken in ODP Presentatie.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Zoek tekst ODP met behulp van C#" h2="Bouw uw eigen .NET-apps om tekst in presentatiebestanden te zoeken en te vervangen met behulp van server-side API's. Leer hoe u alle ingangen van een bepaald woord of een bepaalde woordgroep in presentatiedocumenten kunt vinden. Zoek tekst op basis van exacte gegevensovereenkomst en overeenkomst met reguliere expressies." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Zoek en vervang tekst ODP Presentatie via C#" %}}
Een basisdocument zoeken en tekst vervangen in inhoud, opmerkingen, dia-notities of metadata met Aspose.Slides for .NET API's kan worden gedaan met slechts enkele regels code. Gebruik reguliere expressie-overeenkomsten, zoek hoofdletters en kleine letters om tekst in de presentatie te zoeken. Zoek tekst in titels, inhoud, footer of header.
{{% blocks/products/pf/agp/code-block title="Zoek tekst ODP Presentatie met behulp van C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.odp"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.odp", SaveFormat.Odp);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="Tekst zoeken in ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dit zijn de stappen om ODP tekstbestanden te doorzoeken." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laad ODP met een instantie van Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Gebruik de methode [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/) om tekst te zoeken en te vervangen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Sla resultaat op in ODP formaat
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Zoek live demo's" sectionDescription="Zoek en vervang nu tekst in inhoud, opmerkingen of metadata in ODP documenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde zoekformaten" subTitle="Met C# kunt u ook tekst zoeken in de volgende indelingen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/nl/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}