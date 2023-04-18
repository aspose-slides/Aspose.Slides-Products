---
title: PPT-Anmerkung mit .NET entfernen
weight: 4380
url: /de/net/annotation/ppt/ 
description: C#-Quellcode zum Löschen von Anmerkungen im PPT-Format auf .NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Kommentare und Kommentarautoren aus PPT in C# entfernen" h2="Erstellen Sie Ihre eigenen .NET-Apps, um Kommentare und Autoren in Dokumentdateien mithilfe serverseitiger APIs zu bearbeiten." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5="ODP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare aus PPT über C# entfernen" %}}
Um Anmerkungen aus der PPT-Datei zu entfernen, verwenden wir die API [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net), die eine funktionsreiche, leistungsstarke und benutzerfreundliche API ist Dokumentbearbeitungs-API für die C#-Plattform.
{{% blocks/products/pf/agp/code-block title="Anmerkungen aus PPT löschen – C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("example.ppt"))
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

{{< blocks/products/pf/feature-page-section  h2="So entfernen Sie Kommentare aus PPT über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Instanz der Präsentationsklasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Iterieren Sie über alle Autoren der geladenen PPT
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/annotation/pptx/" name="PPTX" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}