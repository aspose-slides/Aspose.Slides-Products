---
title: Ta bort ODP Annotation med .NET
weight: 4380
url: /sv/net/annotation/odp/ 
description: C#-källkod för att radera ODP-formatkommentarer på .NET Framework, .NET Core, Windows Azure, Mono eller Xamarin-plattformar.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Ta bort kommentarer och kommentarsförfattare från ODP i C#" h2="Bygg dina egna .NET-appar för att manipulera kommentarer och författare i dokumentfiler med hjälp av API:er på serversidan." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Ta bort kommentarer från ODP via C#" %}}
För att ta bort anteckningar från ODP-filen använder vi [Aspose.Slides for .NET](https://products.aspose.com/slides/sv/net) API som är en funktionsrik, kraftfull och lättanvänd API för dokumentmanipulation för C#-plattformen.
{{% blocks/products/pf/agp/code-block title="Ta bort anteckningar från ODP - C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.odp"))
{
    // Deletes all comments from the presentation
    foreach (var author in presentation.CommentAuthors)
    {
        author.Comments.Clear();
    }

    // Deletes all authors
    presentation.CommentAuthors.Clear();

    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{< blocks/products/pf/feature-page-section  h2="Hur man tar bort kommentarer från ODP via C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installera **Aspose.Slides för .NET**. Se [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ladda ODP med en instans av presentationsklassen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterera över alla författare av laddad ODP
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ta bort alla kommentarer från en författare
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ta bort alla författare i slutet
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra anteckningsformat som stöds" subTitle="Med C# kan man enkelt kommentera andra format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/annotation/pptx/" name="PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/sv/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}