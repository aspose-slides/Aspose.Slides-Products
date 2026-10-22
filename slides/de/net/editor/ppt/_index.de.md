---
lastmod: 2022-12-23
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PPT in C# bearbeiten
url: /de/net/editor/ppt/
keywords: PPT bearbeiten, PowerPoint bearbeiten, PPT, PowerPoint, C#-API, .NET-Bibliothek
description: Bearbeiten Sie PPT in C#. Verwenden Sie die .NET-Bibliotheks-API, um PowerPoint-Präsentationen zu bearbeiten
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PPT in C# bearbeiten" h2="Leistungsstarke plattformübergreifende .NET-API zum Bearbeiten von PPT mit C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" related="PDF,HTML" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PPT in C# bearbeiten" variant="code" %}}

Mit [**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) können Sie mit nur wenigen Codezeilen eine neue Textzeile zu einem PPT-Dokument hinzufügen.

{{< blocks/products/pf/slides-design-update-10-2026/code title="C#-Code zum Bearbeiten von PPT" >}}
```cs
using (Presentation presentation = new Presentation("pres.ppt"))
{
    AutoShape shape = (AutoShape)presentation.Slides[0].Shapes[0];
    shape.TextFrame.Text = "New text";
    presentation.Save("pres.ppt", SaveFormat.Ppt);
}
```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="Bearbeiten Sie PPT mit Aspose.Slides" %}}

[**Aspose.Slides for .NET**](https://products.aspose.com/slides/de/net/) ist eine leistungsstarke .NET-Bibliothek zum Manipulieren und Bearbeiten von Präsentationen. Sie können eine PPT-Präsentation bearbeiten, indem Sie ihr eine neue Textzeile hinzufügen.

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="So bearbeiten Sie PPT in C#" intro="" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Installieren Sie **Aspose.Slides für .NET**. Siehe [**Installation**](https://docs.aspose.com/slides/net/installation/).{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie die Bibliothek als Referenz in Ihrem Projekt hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Erstellen Sie eine Instanz der Presentation-Klasse.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Laden Sie die PPT-Präsentation, die Sie bearbeiten möchten.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Fügen Sie eine neue Textzeile hinzu.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}Speichern Sie die geänderte PowerPoint-Datei.{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/editor-app />}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="Bearbeiten Sie andere Dateien" subTitle="Sie können auch Dateien in anderen Formaten bearbeiten" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/editor/pdf/" name="Edit PDF" >}}    
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/de/net/editor/html/" name="Edit HTML" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
