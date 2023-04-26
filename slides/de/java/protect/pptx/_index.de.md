---
title: PPTX-Präsentationsdateien mit Java schützen
url: /de/java/protect/pptx/
keywords: Schreibschutz PPTX, Verschlüsseln einer PPTX, Sperren von PPTX Präsentation, Schützen von PPTX
description: Java-Quellcode zum Schutz der PPTX-Präsentation.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="PPTX mit Java sperren oder mit Passwort schützen" h2="Erstellen Sie Ihre eigenen Java-Apps, um Präsentationsdateien mit serverseitigen APIs zu schützen." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="Schützen einer PPTX-Präsentation über Java" %}}
Mit Aspose.Slides for Java können Sie Ihre PPTX-Präsentation vor dem Öffnen oder Ändern schützen, indem Sie ein Passwort festlegen. Um die gesperrte Präsentation zu öffnen oder zu ändern, muss ein Benutzer dann das Kennwort eingeben.
{{% blocks/products/pf/agp/code-block title="Verschlüsseln einer PPTX-Präsentation mit Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().encrypt("123123");
    presentation.save("encrypted-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Festlegen des Schreibschutzes für eine PPTX-Präsentation mit Java" offSpacer="true" %}}

```java

Presentation presentation = new Presentation("pres.pptx");
try {
    presentation.getProtectionManager().setWriteProtection("123123");
    presentation.save("write-protected-pres.pptx", SaveFormat.Pptx);
} finally {
    if (presentation != null) presentation.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So schützen Sie PPTX über Java mit einem Passwort" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Schützen von PPTX-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie PPTX mit einer Präsentationsinstanz
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Schützen Sie die Präsentation mit der ProtectionManager-Klasse
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ergebnis im Format PPTX speichern
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte geschützte Formate" subTitle="Mit Java können Sie auch die folgenden Formate schützen:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/protect/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/protect/ppt/" name="PPT" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}