---
title: Conversion de présentation Microsoft PowerPoint en plusieurs fichiers à l'aide de C#
url: /fr/net/conversion/
description: Convertissez les diapositives Microsoft PowerPoint en différents fichiers, notamment les formats PDF, HTML et image sur les plates-formes .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversion de présentation PowerPoint Microsoft<sup>®</sup> via C#" h2="Codes sources C # pour différents cas de conversion pour convertir des fichiers en images, PDF, HTML et autres formats." >}}

{{% blocks/products/pf/feature-page-summary %}}

Il est facile pour les développeurs de convertir des présentations PowerPoint Microsoft<sup>®</sup> avec rapidité et précision. Obtenez les résultats en un rien de temps pour automatiser les processus métier. Nous discutons ici de quelques cas pour lire ou charger n'importe quelle entrée [formats PowerPoint pris en charge](https://docs.aspose.com/slides/net/supported-file-formats/) et écrire ou enregistrer dans n'importe quel format de sortie pris en charge. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Inter-conversion de fichiers Microsoft PowerPoint" %}}
Chaque fois qu'il est nécessaire d'automatiser l'inter-conversion des formats Microsoft<sup>®</sup> PowerPoint. La **bibliothèque PowerPoint C#** fournit des cours pour atteindre cet objectif. Chargez le fichier en utilisant [Classe de présentation](https://apireference.aspose.com/net/slides/aspose.slides/presentation) pour charger ou lire le format souhaité et en appelant la [Méthode Save](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) de la même classe en spécifiant le fichier de sortie et [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Code de conversion C# pour les présentations Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversion C# PowerPoint en PDF" %}}

Pour convertir avec précision les diapositives PowerPoint en PDF, les programmeurs peuvent charger le document à l'aide de la classe Presentation et utiliser [classe PdfOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) pour toutes les options spécifiques et personnalisées. des options telles que le niveau de compression du texte, la qualité Jpeg, le comportement des métafichiers, la conversion de diapositives masquées ainsi que la sélection de diapositives spécifiques, etc. Même il existe une option pour protéger le fichier PDF converti avec un mot de passe.
{{% blocks/products/pf/feature-page-code h3="Code de convertisseur C# PowerPoint en PDF" %}}

```cs
// Load PowerPoint file
Presentation pptxtopdf = new Presentation("sourceFile.pptx");

// Create PdfOptions class object for specific settings
PdfOptions pptPDFOptions = new PdfOptions();

// Set Jpeg quality
pptPDFOptions.JpegQuality = 90;

// Set behavior for metafiles
pptPDFOptions.SaveMetafilesAsPng = true;

// Set text compression level
pptPDFOptions.TextCompression = PdfTextCompression.Flate;

// Define the PDF 15 standard
pptPDFOptions.Compliance = PdfCompliance.Pdf15;

// Include hidden slides
pptPDFOptions.ShowHiddenSlides = true;

// Setting PDF password and access permissions
pptPDFOptions.Password = "password";
pptPDFOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;

// Save the presentation as PDF
pptxtopdf.Save("csharp-PowerPoint-to.pdf", SaveFormat.Pdf, pptPDFOptions);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversion Microsoft PowerPoint en HTML" %}}
Chaque fois qu'il est nécessaire d'intégrer des présentations dans des pages Web, il est nécessaire de convertir les diapositives en HTML. L'API fournit [classe HtmlOptions](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), utilisez-la après avoir chargé les fichiers pour des paramètres spéciaux comme les diapositives masquées, car par défaut, celles-ci ne seront pas être inclus lors du processus de conversion. Passez les options finalisées à la méthode Save pour la conversion.
{{% blocks/products/pf/feature-page-code h3="Code C# pour la conversion de PowerPoint en HTML" %}}

```cs

// Load source presentation 
Presentation powerpoiontohtml = new Presentation("sourceFile.pptx");

// Create HTML options
HtmlOptions PowerPointhtmlOpt = new HtmlOptions();

// Show hidden slides
PowerPointhtmlOpt.ShowHiddenSlides = true;

// Save the PPTX as HTML
powerpoiontohtml.Save("presentation-to.html", SaveFormat.Html, PowerPointhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir des diapositives PowerPoint en formats d'image" %}}
La conversion des formats Microsoft<sup>®</sup> PowerPoint en images JPEG, PNG, TIFF, etc. est un autre cas d'utilisation courant principalement utilisé pour créer des vignettes de diapositives. Le processus de codage est simple. Après avoir chargé le document, utilisez [l'interface ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) pour parcourir chaque diapositive. Au cours de chaque itération, utilisez (Objet Bitmap) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] avec son mehtod GetThumbnail ayant des dimensions d'image personnalisées. Enfin, enregistrez l'image dans le format requis.
{{% blocks/products/pf/feature-page-code h3="C # PowerPoint en code de convertisseur d'image" %}}
```cs
using (Presentation powerpointtoimage = new Presentation("source-file.ppt")){
foreach (ISlide sld in powerpointtoimage.Slides){

// Create a full scale image
Bitmap bmp = sld.GetThumbnail(1f, 1f);
// or use some customized dimensions as sld.GetThumbnail(x, y)

// Save the image
bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), System.Drawing.Imaging.ImageFormat.Jpeg);
}
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}