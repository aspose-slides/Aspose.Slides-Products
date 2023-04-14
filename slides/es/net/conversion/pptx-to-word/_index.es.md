---
title: Convertir PPTX a Word en C#
url: /es/net/conversion/pptx-to-word/
keywords: Convierta PPTX a Word, PPTX a Word, PPTX a DOC, PowerPoint a Word, C# API, Biblioteca .NET
description: Convierte PPTX a Word en C#. Use la API de la biblioteca .NET para convertir PowerPoint a Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PPTX a Word en C#" h2="Potente API .NET multiplataforma para convertir PowerPoint a Word usando código C# en plataformas NET Framework, .NET Core, Windows Azure, Mono o Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Convierta PowerPoint a Word usando Aspose.Slides y Aspose.Words" %}}

[**Aspose.Slides para .NET**](https://products.aspose.com/slides/es/net/) y [**Aspose.Words para .NET**](https://products.aspose. com/words/net/) son potentes bibliotecas .NET que se utilizan para manipular y convertir presentaciones de PowerPoint, documentos de Word y otros archivos. Cuando convierte PowerPoint a Word, básicamente está moviendo el contenido de las diapositivas de una presentación a páginas en un documento de Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convertir PowerPoint a Word en C#" %}}
Puede convertir PPTX a Word rápidamente con solo unas pocas líneas de código

{{% blocks/products/pf/agp/code-block title="Código C# para convertir PowerPoint a Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Cómo convertir PPTX a Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Instale **Aspose.Slides para .NET** y **Aspose.Words para .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Agregue las dos bibliotecas como referencias en su proyecto.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cree una instancia de la clase Presentation y la clase Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Cargue la presentación PPTX que desea convertir a Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Genera imágenes y textos a partir del contenido de las diapositivas.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Guarde el documento de Word resultante.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertidor en línea gratuito" sectionDescription="[Cómo convertir PPT a HTML en Python](https://products.aspose.com/slides/es/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir PowerPoint a archivos en otros formatos" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-html/" name="PPTX TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-jpeg/" name="PPTX TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-png/" name="PPTX TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-svg/" name="PPTX TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-bmp/" name="PPTX TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-emf/" name="PPTX TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/es/net/conversion/pptx-to-gif/" name="PPTX TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}