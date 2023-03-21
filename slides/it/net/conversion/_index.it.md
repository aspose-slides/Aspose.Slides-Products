---
title: Conversione della presentazione di Microsoft PowerPoint in più file utilizzando C#
url: /it/net/conversion/
description: Converti le diapositive di Microsoft PowerPoint in file diversi, inclusi PDF, HTML e formati immagine su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversione di presentazioni PowerPoint di Microsoft<sup>®</sup> tramite C#" h2="Codici sorgente C# per diversi casi di conversione per convertire file in immagini, PDF, HTML e altri formati." >}}

{{% blocks/products/pf/feature-page-summary %}}

È facile per gli sviluppatori convertire presentazioni Microsoft<sup>®</sup> PowerPoint con velocità e precisione. Ottieni i risultati in pochissimo tempo per automatizzare i processi aziendali. Stiamo discutendo qui alcuni casi per leggere o caricare qualsiasi input [formati PowerPoint supportati](https://docs.aspose.com/slides/net/supported-file-formats/) e scrivere o salvare in qualsiasi formato di output supportato. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversione interna di file Microsoft PowerPoint" %}}
Ogni volta che è necessario automatizzare l'interconversione dei formati Microsoft<sup>®</sup> PowerPoint. **Libreria C# PowerPoint** fornisce classi per raggiungere questo obiettivo. Caricare il file utilizzando [Presentation class](https://apiference.aspose.com/net/slides/aspose.slides/presentation) per caricare o leggere il formato desiderato e chiamando il [Save method](https://apiference. aspose.com/slides/net/aspose.slides/presentation/methods/save) della stessa classe specificando il file di output e [SaveFormat](https://apiference.aspose.com/slides/net/aspose.slides.export /salvaformato).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Codice del convertitore C# per presentazioni di Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversione da C# PowerPoint a PDF" %}}

Per convertire in modo accurato le diapositive PowerPoint in PDF, i programmatori possono caricare il documento utilizzando la classe Presentation e utilizzare la [classe PdfOptions](https://apiference.aspose.com/slides/net/aspose.slides.export/pdfoptions) per tutti specifici e personalizzati opzioni come il livello di compressione del testo, la qualità Jpeg, il comportamento dei metafile, la conversione di diapositive nascoste, nonché la selezione di diapositive specifiche e altro ancora. Anche c'è un'opzione per proteggere il file PDF convertito con una password.
{{% blocks/products/pf/feature-page-code h3="Codice di conversione da PowerPoint a PDF C#" %}}

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
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf pdf-to-html pdf-to-image pdf-to-jpg pdf-to-png pdf-to-svg pdf-to-tiff pdf-to-xml" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversione da Microsoft PowerPoint a HTML" %}}
Ogni volta che è necessario incorporare presentazioni all'interno di pagine Web, è necessario convertire le diapositive in HTML. L'API fornisce [classe HtmlOptions](https://apiference.aspose.com/slides/net/aspose.slides.export/htmloptions), Usalo dopo aver caricato i file per impostazioni speciali come le diapositive nascoste, poiché per impostazione predefinita, queste non lo faranno essere inclusi durante il processo di conversione. Passa le opzioni finalizzate al metodo Salva per la conversione.
{{% blocks/products/pf/feature-page-code h3="Codice C# per la conversione da PowerPoint a HTML" %}}

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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html html-to-image html-to-jpg html-to-pdf html-to-tiff html-to-xml" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti diapositive PowerPoint in formati immagine" %}}
La conversione dei formati Microsoft<sup>®</sup> PowerPoint in immagini JPEG, PNG, TIFF ecc. è un altro caso d'uso comune utilizzato principalmente per la creazione di miniature di diapositive. Il processo di codifica è semplice. Dopo aver caricato il documento, utilizzare [ISlide interface](https://apiference.aspose.com/net/slides/aspose.slides/islide) per scorrere ogni diapositiva. Durante ogni iterazione, utilizzare (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] insieme al relativo metodo GetThumbnail con dimensioni dell'immagine personalizzate. Infine salva l'immagine nel formato richiesto.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint in codice convertitore di immagini" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp image-to-jpg image-to-pdf jpg-to-image jpg-to-pdf jpg-to-png png-to-jpg png-to-pdf png-to-svg svg-to-png" >}}