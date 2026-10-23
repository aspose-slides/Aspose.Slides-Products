---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PDF in C# bearbeiten
url: /de/net/editor/pdf/
keywords: Bearbeiten Sie PDF, PDF, C#-API, .NET-Bibliothek
description: PDF-Dateien in C# bearbeiten. Verwenden Sie die .NET-Bibliotheks-API, um PDF-Dokumente zu bearbeiten
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PDF in C# bearbeiten" h2="Leistungsstarke plattformübergreifende .NET-API zum Bearbeiten von PDF-Dateien mit C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" related="PPT,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PDF in C# bearbeiten" variant="code" %}}

Mit [**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) können Sie mit nur wenigen Codezeilen eine neue Textzeile zu einem PDF-Dokument hinzufügen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-Code zum Bearbeiten von PDF" >}}
```cs
using (Presentation pres = new Presentation())
{
    pres.Slides.RemoveAt(0); // remove default empty slide
    pres.Slides.AddFromPdf("doc.pdf");

    AutoShape shape = (AutoShape)pres.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";

    pres.Save("doc.pdf", SaveFormat.Pdf);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bearbeiten Sie PDF mit Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke .NET-Bibliothek zum Manipulieren und Bearbeiten von Präsentationen, PDF-Dokumenten und anderen Dateien. Sie können ein PDF-Dokument bearbeiten, indem Sie ihm eine neue Textzeile hinzufügen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So bearbeiten Sie PDFs in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides für .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie eine Instanz der Presentation-Klasse.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie das PDF-Dokument, das Sie bearbeiten möchten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie eine neue Textzeile hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geänderte PDF-Datei.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app label="Entwickelt mit Aspose.Slides" title="PPTX-Dateien online bearbeiten" description="Die kostenlose App Aspose.Slides Editor basiert auf [Aspose.Slides for .NET](https://products.aspose.com/slides/de/net/), derselben API wie im obigen Code. Öffnen Sie sie und sehen Sie, was die API mit Ihren eigenen PPTX-Dateien leisten kann." button="Aspose.Slides Editor öffnen" note="[Alle kostenlosen Apps](https://products.aspose.app/slides/family)" >}}
- Läuft im Browser, keine Installation erforderlich.
- Sehen Sie, wie Aspose.Slides Ihre Dateien verarbeitet, bevor Sie Code schreiben.
- Laden Sie Ihre PPTX-Dateien hoch und bearbeiten Sie sie sofort.
- Speichern Sie die bearbeitete Datei und laden Sie sie herunter.
{{< /blocks/products/pf/slides-design-update-10-2026/editor-app >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bearbeiten Sie andere Dateien" subTitle="Sie können auch Dateien in anderen Formaten bearbeiten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/editor/ppt/" name="Edit PPT" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
