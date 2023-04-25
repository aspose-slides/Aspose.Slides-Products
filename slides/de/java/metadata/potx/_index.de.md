---
title: Metadaten von POTX-Dateien mit Java anzeigen oder bearbeiten
url: /de/java/metadata/potx/
keywords: POTX-Metadaten bearbeiten, POTX-Metadaten anzeigen, POTX-Eigenschaften bearbeiten, POTX-Eigenschaften anzeigen
description: Java-Quellcode zum Bearbeiten oder Anzeigen von Metadaten im POTX-Format.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="POTX-Eigenschaften mit Java bearbeiten" h2="Erstellen Sie Ihre eigenen Java-Apps, um integrierte und benutzerdefinierte Eigenschaften in Präsentationsdateien mithilfe serverseitiger APIs zu ändern." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/slides/aspose_slides-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTX" pfName="Aspose.Slides" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="PPT" fileiconsmall2="PPTX" fileiconsmall3="ODP" fileiconsmall4="POT" fileiconsmall5="ppsx" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Slides " subTitlepfName="for Java" >}}

{{% blocks/products/pf/feature-page-section  h2="POTX-Eigenschaften über Java ändern" %}}
Mit Aspose.Slides for Java können Entwickler auf die Werte integrierter Eigenschaften sowie benutzerdefinierter Eigenschaften zugreifen und diese ändern. Entwickler können die vom Präsentationsobjekt bereitgestellte Eigenschaft [DocumentProperties](https://reference.aspose.com/slides/java/com.aspose.slides/documentproperties/) verwenden, um auf die Dokumenteigenschaften der Präsentationsdatei zuzugreifen.
{{% blocks/products/pf/agp/code-block title="POTX integrierte Eigenschaften ändern – Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation("Presentation.potx");
try {
    // Create a reference to IDocumentProperties object associated with Presentation
    IDocumentProperties dp = pres.getDocumentProperties();
    
    // Set the built-in properties
    dp.setAuthor("Aspose.Slides for Java");
    dp.setTitle("Modifying Presentation Properties");
    dp.setSubject("Aspose Subject");
    dp.setComments("Aspose Description");
    dp.setManager("Aspose Manager");
    
    // Save your presentation to a file
    pres.save("DocProps.potx", SaveFormat.Potx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Benutzerdefinierte Eigenschaften zu POTX hinzufügen – Java" offSpacer="true" %}}

```java

Presentation pres = new Presentation();
try {
    // Getting Document Properties
    IDocumentProperties dProps = pres.getDocumentProperties();
    
    // Adding Custom properties
    dProps.set_Item("New Custom", 12);
    dProps.set_Item("My Name", "Aspose Metadata Editor");
    dProps.set_Item("Custom", 124);
    
    // Getting property name at particular index
    String getPropertyName = dProps.getCustomPropertyName(2);
    
    // Removing selected property
    dProps.removeCustomProperty(getPropertyName);
    
    // Saving presentation
    pres.save("CustomDemo.potx", SaveFormat.Potx);
} finally {
    if (pres != null) pres.dispose();
}
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So extrahieren Sie Metadaten von POTX über Java" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte zum Extrahieren von Metadaten aus POTX-Dateien." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Instanziieren Sie die Präsentationsklasse mit dem Pfad zur Datei POTX
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Holen Sie sich das DocumentProperties-Objekt, das der Präsentation zugeordnet ist
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Schleife über die Elemente im DocumentProperties-Objekt
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Greifen Sie auf benutzerdefinierte Eigenschaften zu und ändern Sie sie
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Metadatenformate" subTitle="Mit Java können Sie auch Metadaten vieler anderer Formate bearbeiten, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/ppt/" name="PPT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/metadata/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}