---
title: Entfernen Sie die PPTX-Anmerkung mit .NET
weight: 4380
url: /de/net/annotation/pptx/ 
description: C#-Quellcode zum Löschen von Anmerkungen im PPTX-Format auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Kommentare und Kommentarautoren aus PPTX in C# entfernen" h2="Erstellen Sie Ihre eigenen .NET-Apps, um Kommentare und Autoren in Dokumentdateien mithilfe serverseitiger APIs zu bearbeiten." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare aus PPTX über C# entfernen" %}}
Um Anmerkungen aus der PPTX-Datei zu entfernen, verwenden wir die API [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net), die eine funktionsreiche, leistungsstarke und benutzerfreundliche API ist Dokumentbearbeitungs-API für die C#-Plattform.
{{% blocks/products/pf/agp/code-block title="Anmerkungen aus PPTX löschen – C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.pptx"))
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

{{< blocks/products/pf/feature-page-section  h2="So entfernen Sie Kommentare aus PPTX über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Instanz der Präsentationsklasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Über alle Autoren von geladenem PPTX iterieren
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Alle Kommentare eines Autors entfernen
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Entfernen Sie am Ende alle Autoren
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Anmerkungsformate" subTitle="Mit C# kann man problemlos andere Formate kommentieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/annotation/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/annotation/ppt/" name="PPT" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}