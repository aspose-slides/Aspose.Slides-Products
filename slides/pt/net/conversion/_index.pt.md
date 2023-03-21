---
title: Conversão de apresentação do Microsoft PowerPoint para vários arquivos usando C#
url: /pt/net/conversion/
description: Converta slides do Microsoft PowerPoint para diferentes arquivos, incluindo PDF, HTML e formatos de imagem nas plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Conversão de apresentação do Microsoft<sup>®</sup> PowerPoint via C#" h2="Códigos fonte C# para diferentes casos de conversão para converter arquivos em imagens, PDF, HTML e outros formatos." >}}

{{% blocks/products/pf/feature-page-summary %}}

É fácil para os desenvolvedores converter apresentações do Microsoft<sup>®</sup> PowerPoint com velocidade e precisão. Obtenha os resultados em pouco tempo para automatizar os processos de negócios. Estamos discutindo aqui alguns casos para ler ou carregar qualquer entrada [formatos PowerPoint suportados](https://docs.aspose.com/slides/net/supported-file-formats/) e gravar ou salvar em qualquer formato de saída suportado. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Interconversão de arquivos do Microsoft PowerPoint" %}}
Sempre que houver necessidade de automatizar a interconversão de formatos Microsoft<sup>®</sup> PowerPoint. A **biblioteca PowerPoint C#** fornece classes para atingir esse objetivo. Carregue o arquivo usando [Classe de apresentação](https://apireference.aspose.com/net/slides/aspose.slides/presentation) para carregar ou ler o formato desejado e chamar o [método Salvar](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) da mesma classe especificando o arquivo de saída e [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Código Conversor C# para Apresentações do Microsoft PowerPoint" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint para conversão de PDF" %}}

Para converter slides do PowerPoint para PDF com precisão, os programadores podem carregar o documento usando a classe Presentation e usar [PdfOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) para todas as opções específicas e personalizadas opções como nível de compactação de texto, qualidade Jpeg, comportamento de meta-arquivos, conversão de slides ocultos, seleção de slides específicos e muito mais. Mesmo existe a opção de proteger o arquivo PDF convertido com senha.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint para código de conversão de PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Conversão do Microsoft PowerPoint para HTML" %}}
Sempre que houver necessidade de incorporar apresentações em páginas da Web, será necessário converter slides em HTML. A API fornece [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions), use-o após carregar os arquivos para configurações especiais, como slides ocultos, pois, por padrão, eles não serão ser incluído durante o processo de conversão. Passe as opções finalizadas para Salvar método para conversão.
{{% blocks/products/pf/feature-page-code h3="Código C# para conversão de PowerPoint para HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Converter slides do PowerPoint para formatos de imagem" %}}
A conversão de formatos do Microsoft<sup>®</sup> PowerPoint para imagens JPEG, PNG, TIFF etc é outro caso de uso comum usado principalmente para criar miniaturas de slides. O processo de codificação é simples. Após carregar o documento, use a [interface ISlide](https://apireference.aspose.com/net/slides/aspose.slides/islide) para percorrer cada slide. Durante cada iteração, use (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] junto com seu método GetThumbnail com dimensões de imagem personalizadas. Por fim, salve a imagem no formato necessário.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint para código do conversor de imagem" %}}
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