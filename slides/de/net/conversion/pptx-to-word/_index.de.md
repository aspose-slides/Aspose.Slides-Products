---
title: Konvertieren Sie PPTX in Word in C#
url: /de/net/conversion/pptx-to-word/
keywords: Konvertieren Sie PPTX in Word, PPTX in Word, PPTX in DOC, PowerPoint in Word, C#-API, .NET-Bibliothek
description: Konvertieren Sie PPTX in C# in Word. Verwenden Sie die .NET-Bibliotheks-API, um PowerPoint in Word zu konvertieren
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie PPTX in Word in C#" h2="Leistungsstarke plattformübergreifende .NET-API zum Konvertieren von PowerPoint in Word mithilfe von C#-Code auf NET Framework-, .NET Core-, Windows Azure-, Mono- oder Xamarin-Plattformen" >}}

{{% blocks/products/pf/feature-page-section h2="Konvertieren Sie PowerPoint mit Aspose.Slides und Aspose.Words in Word" %}}

[**Aspose.Slides für .NET**](https://products.aspose.com/slides/de/net/) und [**Aspose.Words für .NET**](https://products.aspose. com/words/net/) sind leistungsstarke .NET-Bibliotheken zum Bearbeiten und Konvertieren von PowerPoint-Präsentationen, Word-Dokumenten und anderen Dateien. Wenn Sie PowerPoint in Word konvertieren, verschieben Sie im Wesentlichen die Inhalte der Folien einer Präsentation auf Seiten in einem Word-Dokument.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie PowerPoint in Word in C#" %}}
Mit nur wenigen Codezeilen können Sie PPTX schnell in Word konvertieren

{{% blocks/products/pf/agp/code-block title="C#-Code zum Konvertieren von PowerPoint in Word" offSpacer="true" %}}
```cs
using var presentation = new Presentation();
var doc = new Document();
var builder = new DocumentBuilder(doc);
foreach (var slide in presentation.Slides)
{
    // generates and inserts slide image
    using var bitmap = slide.GetThumbnail(1, 1);
    using var stream = new MemoryStream();
    bitmap.Save(stream, ImageFormat.Png);
    stream.Seek(0, SeekOrigin.Begin);
    using var skBitmap = SKBitmap.Decode(stream);
    builder.InsertImage(skBitmap);

    // inserts slide texts
    foreach (var shape in slide.Shapes)
    {
        if (shape is AutoShape autoShape)
        {
            builder.Writeln(autoShape.TextFrame.Text);
        }
    }

    builder.InsertBreak(BreakType.PageBreak);
}
doc.Save("document.docx");
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="So konvertieren Sie PPTX in Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installieren Sie **Aspose.Slides für .NET** und **Aspose.Words für .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Fügen Sie die beiden Bibliotheken als Referenzen in Ihrem Projekt hinzu.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Erstellen Sie eine Instanz der Presentation-Klasse und der Doc-Klasse.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Laden Sie die PPTX-Präsentation, die Sie in Word konvertieren möchten.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Generieren Sie Bilder und Texte basierend auf den Inhalten der Folien.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Speichern Sie das resultierende Word-Dokument.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Kostenloser Online-Konverter" sectionDescription="[So konvertieren Sie PPT in HTML in Python](https://products.aspose.com/slides/de/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="Sie können PowerPoint auch in Dateien in anderen Formaten konvertieren" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/de/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}