---
title: Suchen Sie Text in PPT-Präsentationsdateien mit .NET
url: /de/net/search/ppt/
keywords: Wörter in PPT suchen, Text in PPT suchen und ersetzen, Text in PPT suchen. Präsentation
description: C#-Quellcode zum Durchsuchen von Text in der PPT-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Suchen Sie nach Text PPT mit C#" h2="Erstellen Sie Ihre eigenen .NET-Apps zum Suchen und Ersetzen von Text in Präsentationsdateien mithilfe serverseitiger APIs. Erfahren Sie, wie Sie alle Einträge eines bestimmten Worts oder einer bestimmten Phrase in Präsentationsdokumenten finden. Durchsuchen Sie Text nach exaktem Datenabgleich und regulärem Ausdrucksabgleich." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="Aspose.Slides" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for .NET" >}}

{{% blocks/products/pf/feature-page-section  h2="Text suchen und ersetzen PPT Präsentation über C#" %}}
Eine einfache Dokumentsuche und das Ersetzen von Text in Inhalten, Kommentaren, Foliennotizen oder Metadaten mit Aspose.Slides for .NET-APIs kann mit nur wenigen Codezeilen durchgeführt werden. Verwenden Sie den Abgleich regulärer Ausdrücke und achten Sie auf die Groß-/Kleinschreibung, um Text in der Präsentation zu durchsuchen. Suchen Sie nach Text in Titeln, Inhalten, Fußzeilen oder Kopfzeilen.
{{% blocks/products/pf/agp/code-block title="Suchtext PPT Präsentation mit C#" offSpacer="true" %}}

```cs

using (Presentation presentation = new Presentation("welcome-to-powerpoint.ppt"))
{
    Aspose.Slides.Util.SlideUtil.FindAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.Save("replaced.ppt", SaveFormat.Ppt);
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So suchen Sie Text in PPT über C#" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Durchsuchen von Textdateien im PPT-Format." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPT mit einer Instanz von Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwenden Sie die Methode [FindAndReplaceText](https://reference.aspose.com/slides/net/aspose.slides.util/slideutil/findandreplacetext/), um Text zu suchen und zu ersetzen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPT speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online PPT Live-Demos durchsuchen" sectionDescription="Suchen und ersetzen Sie jetzt Text in Inhalten, Kommentaren oder Metadaten in PPT-Dokumenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Suchformate" subTitle="Mit C# können Sie auch nach Text in den folgenden Formaten suchen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/search/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}