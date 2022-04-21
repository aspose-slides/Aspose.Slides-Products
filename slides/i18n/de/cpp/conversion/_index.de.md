---
title: Konvertierung von Microsoft PowerPoint-Präsentationen in verschiedene Formate mit C++
url: /de/cpp/conversion/
description: Konvertieren Sie Microsoft PowerPoint-Folien in mehrere Dateien, einschließlich HTML-, PDF- und Bildformate in C++-basierten Anwendungen.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertierung von Microsoft<sup>®</sup> PowerPoint-Präsentationen über C++" h2="C++-Beispielcodes für verschiedene Konvertierungsszenarien zum Konvertieren von Folien in Bilder, HTML, PDF und andere Formate." >}}

{{% blocks/products/pf/feature-page-summary %}}

Der Konvertierungsprozess von Microsoft<sup>®</sup> PowerPoint-Formaten ist einfach und leicht zu automatisierende Prozesse mit der C++ PowerPoint-Bibliothek. Entwickler können relevanten Quellcode erweitern und in ihre Anwendungen integrieren. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Zwischenkonvertierung von Microsoft PowerPoint-Formaten" %}}
Die programmgesteuerte Umwandlung von Microsoft<sup>®</sup> PowerPoint-Dokumenten, einschließlich PPT, PPTX, ist nur ein zweizeiliger Code. Laden Sie die Datei mit [Präsentationsklasse](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) und Aufrufen der [Save-Methode](https://apireference.aspose.com/slides /cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) mit der Ausgabedatei und SaveFormat.OutputFormats als Parameter.

{{% blocks/products/pf/feature-page-code h3="C++-Konvertierungscode" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "interconversion-of-powerpoint-files.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint-Dateien in PDF" %}}

Das Konvertieren von Microsoft<sup>®</sup> PowerPoint in PDF ist ein häufiges Szenario, da PDF-Dokumente in großem Umfang geteilt werden. Programmierer können es automatisieren und die relevanten PDF-Konvertierungseinstellungen mit [PdfOptions class](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options) festlegen. Einige der spezifischen Einstellungen wie Textkomprimierungsstufe, JPEG-Qualität [JpegQuality](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#a6bbf3bd303430757aa85ac9e3d184861), PDF-Konformitätsstufe [Konformität](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#aa9dfc92dd22455248ac171c24876cb8f), Konvertieren von versteckten Folien [ShowHiddenSlides](https://apireference.aspose.com/slides/cpp/class /aspose.slides.export.pdf_options#ad11e5a17110d70456df91cc1a5dade23), ausgewählte Folien und Generieren von gesperrten [Kennwort](https://apireference.aspose.com/slides/cpp/class/aspose.slides.export.pdf_options#ab42606dbbf983fe00cc45a19565391a7) geschützten PDF-Dateien .

{{% blocks/products/pf/feature-page-code h3="C++-PowerPoint-zu-PDF-Konvertierungscode" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "powerpoint-to-pdf-conversion.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Speichern Sie Microsoft PowerPoint-Folien als Bilder" %}}
Wann immer es darum geht, Präsentationsinhalte im Web anzuzeigen, müssen Dateien als HTML oder Bilder als JPG, TIFF, PNG usw. gerendert werden. Der Vorgang zum Konvertieren von Folien in Bilder ist einfach. Rufen Sie alle Folien mit [get_Slides()](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#a9981b38f5a01d9fa5482f05b0a75974c) ab und durchlaufen Sie jede Folie einzeln. Verwenden Sie während jeder Iteration [ISlide->GetThumbnail](https://apireference.aspose.com/slides/cpp/class/aspose.slides.i_slide#a7bd377d403ff886232df21351c1fe783) für das Folienbild und speichern Sie es dann im erforderlichen Bildformat. 

{{% blocks/products/pf/feature-page-code h3="C++ PowerPoint-zu-Bild-Konvertierung" %}}

{{< gist "aspose-com-gists" "c408b7aac79956e1dd0f359e07bbc15a" "save-powerpoint-slides-as-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}