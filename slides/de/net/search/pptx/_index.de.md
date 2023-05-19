---
title: Suchen Sie Text in PPTX-Präsentationsdateien mit .NET
url: /de/net/search/pptx/
keywords: Wörter in PPTX suchen, Text in PPTX suchen und ersetzen, Text in PPTX suchen. Präsentation
description: C#-Quellcode zum Durchsuchen von Text in der PPTX-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Suchen Sie nach Text PPTX mit C#" h2="Erstellen Sie Ihre eigenen .NET-Apps zum Suchen und Ersetzen von Text in Präsentationsdateien mithilfe serverseitiger APIs. Erfahren Sie, wie Sie alle Einträge eines bestimmten Worts oder einer bestimmten Phrase in Präsentationsdokumenten finden. Durchsuchen Sie Text nach exaktem Datenabgleich und regulärem Ausdrucksabgleich." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Text suchen und ersetzen PPTX Präsentation über C#" %}}
Eine einfache Dokumentsuche und das Ersetzen von Text in Inhalten, Kommentaren, Foliennotizen oder Metadaten mit Aspose.Slides for .NET-APIs kann mit nur wenigen Codezeilen durchgeführt werden. Verwenden Sie den Abgleich regulärer Ausdrücke und achten Sie auf die Groß-/Kleinschreibung, um Text in der Präsentation zu durchsuchen. Suchen Sie nach Text in Titeln, Inhalten, Fußzeilen oder Kopfzeilen.
{{% blocks/products/pf/agp/code-block title="Suchtext PPTX Präsentation mit C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.pptx"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.pptx", SaveFormat.Pptx);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So suchen Sie Text in PPTX über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Durchsuchen von Textdateien im PPTX-Format." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Instanz von Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwenden Sie die Methode [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/), um Text zu suchen und zu ersetzen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPTX speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPTX Live-Demos durchsuchen" sectionDescription="Suchen und ersetzen Sie jetzt Text in Inhalten, Kommentaren oder Metadaten in PPTX-Dokumenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Suchformate" subTitle="Mit C# können Sie auch nach Text in den folgenden Formaten suchen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/search/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}