---
title: Führen Sie PDF, PPT, PPTX und viele andere Dateiformate mit Java zusammen
url: /de/java/merger/
keywords: Zusammenführen, Verbinden, PowerPoint, Präsentation, Java, Aspose
description: Führen Sie mehrere Dateien in Java PPT, PPTX, ODP, PDF, PNG, JPG und vielen mehr zusammen.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Führen Sie Powerpoint, PDF, PPT oder andere Dokumente in Java zusammen" h2="Hochgeschwindigkeits-Java-Bibliothek zum Zusammenführen von PPT, PPTX, PDF, PNG, JPEG und anderen Formaten." >}}

{{% blocks/products/pf/feature-page-section h2="PPT, PPTX, PDF mit Java zusammenführen" %}}

[**Aspose.Slides for Java**](https://products.aspose.com/slides/de/java/) ist eine leistungsstarke Java-Bibliothek zum Erstellen und Bearbeiten von Präsentationsdateien. Darüber hinaus bietet es flexible Möglichkeiten, mehrere PPT/PPTX-Präsentationen zu kombinieren. Wenn Sie eine Präsentation mit einer anderen zusammenführen, kombinieren Sie deren Folien effektiv in einer einzigen Präsentation, um eine Datei zu erhalten. Mit Aspose.Slides können Sie zwei Präsentationen auf unterschiedliche Weise zusammenführen. Sie können Präsentationen mit all ihren Formen, Stilen, Texten, Formatierungen, Kommentaren, Animationen usw. zusammenführen, ohne sich um Qualitäts- oder Datenverluste sorgen zu müssen.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint-Präsentationen in Java zusammenführen" %}}
Um die PowerPoint-Präsentationen zusammenzuführen, müssen Sie die Folien von einer Präsentation zur anderen klonen.

{{% blocks/products/pf/agp/code-block title="PPTX-Dateien mit Java zusammenführen" offSpacer="true" %}}

```java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge slides
for (ISlide slide : presentation2.getSlides()) {
	// Merge slides from source to target
	presentation1.getSlides().addClone(slide);
}

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Führen Sie Präsentationen mit Slide Master mit Java zusammen" %}}
Dieser Java-Code zeigt, wie Sie mehrere Präsentationen zu einer zusammenführen und Stile aus der Folienmaster-Präsentationsvorlage anwenden. Die Ergebnispräsentation behält also die gleiche Quellformatierung bei und enthält die Formatierung der Masterfolie einer anderen Präsentation.

{{% blocks/products/pf/agp/code-block title="Führen Sie mehrere PPT in Java zu einer einzigen zusammen" offSpacer="true" %}}

``` java

// Load first presentation
Presentation presentation1 = new Presentation("presentation1.pptx");

// Load second presentation
Presentation presentation2 = new Presentation("presentation2.pptx");

// Merge first two slides only using slide master
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(0), presentation1.getMasters().get_Item(0), true);
presentation1.getSlides().addClone(presentation2.getSlides().get_Item(1), presentation1.getMasters().get_Item(0), true);

// Save the presentation
presentation1.save("merged-presentation.pptx", SaveFormat.Pptx);
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="So führen Sie Präsentationen mit Aspose.Slides for Java API zusammen" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="Dies sind die Schritte, um zwei PPTX-Dateien zusammenzuführen und das Ergebnis als PDF in Java zu speichern." >}}

{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie [**Aspose.Slides für Java**](https://docs.aspose.com/slides/java/installation/). 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie Ihrem Java-Projekt eine Bibliotheksreferenz hinzu (importieren Sie die Bibliothek).
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Öffnen Sie die Quell-PPTX-Dateien in Java.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Kombinieren Sie PPTX-Dateien mit der Methode **addClone**.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Präsentation speichern und Ergebnis als einzelne PDF-Datei erhalten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Formate zum Zusammenführen" subTitle="Sie können auch andere Dateiformate kombinieren. Weitere unterstützte Formate finden Sie weiter unten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/otp/" name="OTP" description="OpenDocument Standard Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/pot/" name="POT" description="Microsoft PowerPoint Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/potm/" name="POTM" description="Microsoft PowerPoint Template File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/potx/" name="POTX" description="Microsoft PowerPoint Template Presentation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/pps/" name="PPS" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/ppsm/" name="PPSM" description="Macro-enabled Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/ppsx/" name="PPSX" description="PowerPoint Slide Show" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/ppt/" name="PPT" description="Microsoft PowerPoint 97-2003" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/pptm/" name="PPTM" description="Macro-enabled Presentation File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/java/merger/pptx/" name="PPTX" description="Open XML presentation Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}