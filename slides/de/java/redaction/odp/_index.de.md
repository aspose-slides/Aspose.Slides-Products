---
title: Redigieren Sie ODP-Präsentationsdateien mit Java
url: /de/java/redaction/odp/
keywords: ODP schwärzen, Text in ODP suchen und ersetzen, ODP-Präsentation aktualisieren
description: Java-Quellcode zum Suchen und Ersetzen von Text in der ODP-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ODP mit Java redigieren" h2="Erstellen Sie Ihre eigenen Java-Apps, um mithilfe serverseitiger APIs Text in Präsentationsdateien zu suchen und zu ersetzen. Erfahren Sie, wie Sie Text in Inhalten, Kommentaren oder Metadaten von ODP-Präsentationen suchen und ersetzen" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Redigieren Sie die ODP-Präsentation über Java" %}}
Eine einfache Dokumentsuche und das Ersetzen von Text in Inhalten, Kommentaren, Foliennotizen oder Metadaten mit Aspose.Slides for Java-APIs kann mit nur wenigen Codezeilen durchgeführt werden. Suchen und ersetzen Sie Text in PowerPoint und OpenOffice. Bearbeiten Sie Text, Kommentare und Metadaten in der Präsentation über den Regexp-Datenabgleich.
{{% blocks/products/pf/agp/code-block title="ODP-Präsentation mit Java redigieren" offSpacer="true" %}}

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

{{< blocks/products/pf/feature-page-section  h2="So redigieren Sie ODP über Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Schwärzen von ODP-Dateien." >}}

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

{{< blocks/products/pf/agp/demobox sectionTitle="Online-Redaktions-Live-Demos von ODP" sectionDescription="Suchen und ersetzen Sie jetzt Text in Inhalten, Kommentaren oder Metadaten in ODP-Dokumenten." >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Schwärzungsformate" subTitle="Mit Java können Sie auch die folgenden Formate redigieren:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/redaction/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/redaction/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}