---
title: Convertir PPT en Word en C#
url: /fr/net/conversion/ppt-to-word/
keywords: Convertir PPT en Word, PPT en Word, PPT en DOC, PowerPoint en Word, API C#, bibliothèque .NET
description: Convertissez PPT en Word en C#. Utiliser l'API de la bibliothèque .NET pour convertir PowerPoint en Word
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="Convertir PPT en Word en C#" h2="Puissante API .NET multiplateforme pour convertir PowerPoint en Word à l'aide de code C# sur les plates-formes NET Framework, .NET Core, Windows Azure, Mono ou Xamarin" >}}

{{% blocks/products/pf/feature-page-section h2="Convertir PowerPoint en Word en utilisant Aspose.Slides et Aspose.Words" %}}

[**Aspose.Slides pour .NET**](https://products.aspose.com/slides/fr/net/) et [**Aspose.Words pour .NET**](https://products.aspose. com/words/net/) sont de puissantes bibliothèques .NET utilisées pour manipuler et convertir des présentations PowerPoint, des documents Word et d'autres fichiers. Lorsque vous convertissez PowerPoint en Word, vous déplacez essentiellement le contenu des diapositives d'une présentation vers des pages d'un document Word.

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="Convertir PowerPoint en Word en C#" %}}
Vous pouvez convertir PPT en Word rapidement avec seulement quelques lignes de code

{{% blocks/products/pf/agp/code-block title="Code C# pour convertir PowerPoint en Word" offSpacer="true" %}}
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




{{< blocks/products/pf/feature-page-section  h2="Comment convertir PPT en Word" >}}


{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
Installez **Aspose.Slides pour .NET** et **Aspose.Words pour .NET** 
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Ajoutez les deux bibliothèques en tant que références dans votre projet.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Créez une instance de la classe Presentation et de la classe Doc.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Chargez la présentation PPT que vous souhaitez convertir en Word.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Générez des images et des textes en fonction du contenu des diapositives.
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
Enregistrez le document Word résultant.
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/slides-app-widget  appName="conversion" extension="" sectionTitle="Convertisseur en ligne gratuit" sectionDescription="[Comment convertir PPT en HTML en Python](https://products.aspose.com/slides/fr/en/python-net/conversion/ppt-to-html/)" >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="Vous pouvez également convertir PowerPoint en fichiers dans d'autres formats" >}}


{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-html/" name="PPT TO HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-jpeg/" name="PPT TO JPEG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-png/" name="PPT TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-svg/" name="PPT TO SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-bmp/" name="PPT TO BMP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-emf/" name="PPT TO EMF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/fr/net/conversion/ppt-to-gif/" name="PPT TO GIF" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}