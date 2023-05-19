---
title: Suchen Sie Text in ODP-Präsentationsdateien mit Java
url: /de/java/search/odp/
keywords: Wörter in ODP suchen, Text in ODP suchen und ersetzen, Text in ODP suchen. Präsentation
description: Java-Quellcode zum Durchsuchen von Text in der ODP-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Suchen Sie nach Text ODP mit Java" h2="Erstellen Sie Ihre eigenen Java-Apps zum Suchen und Ersetzen von Text in Präsentationsdateien mithilfe serverseitiger APIs. Erfahren Sie, wie Sie alle Einträge eines bestimmten Worts oder einer bestimmten Phrase in Präsentationsdokumenten finden. Durchsuchen Sie Text nach exaktem Datenabgleich und regulärem Ausdrucksabgleich." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Text suchen und ersetzen ODP Präsentation über Java" %}}
Eine einfache Dokumentsuche und das Ersetzen von Text in Inhalten, Kommentaren, Foliennotizen oder Metadaten mit Aspose.Slides for Java-APIs kann mit nur wenigen Codezeilen durchgeführt werden. Verwenden Sie den Abgleich regulärer Ausdrücke und achten Sie auf die Groß-/Kleinschreibung, um Text in der Präsentation zu durchsuchen. Suchen Sie nach Text in Titeln, Inhalten, Fußzeilen oder Kopfzeilen.
{{% blocks/products/pf/agp/code-block title="Suchtext ODP Präsentation mit Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("welcome-to-powerpoint.odp");
try {
    SlideUtil.findAndReplaceText(presentation, true, "PowerPoint", "Aspose.Slides", null);
    presentation.save("replaced.odp", SaveFormat.Odp);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So suchen Sie Text in ODP über Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Durchsuchen von Textdateien im ODP-Format." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie ODP mit einer Instanz von Presentation.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Verwenden Sie die Methode [FindAndReplaceText](https://reference.aspose.com/slides/java/com.aspose.slides/slideutil/#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-), um Text zu suchen und zu ersetzen.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format ODP speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/demobox sectionTitle="Online ODP Live-Demos durchsuchen" sectionDescription="Suchen und ersetzen Sie jetzt Text in Inhalten, Kommentaren oder Metadaten in ODP-Dokumenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Suchformate" subTitle="Mit Java können Sie auch nach Text in den folgenden Formaten suchen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/search/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/search/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}