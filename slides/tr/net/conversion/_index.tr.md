---
title: Microsoft PowerPoint Sunumunu C# Kullanarak Birden Çok Dosyaya Dönüştürme
url: /tr/net/conversion/
description: Microsoft PowerPoint Slaytlarını .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında PDF, HTML ve görüntü formatları dahil olmak üzere farklı dosyalara dönüştürün.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# ile Microsoft<sup>®</sup> PowerPoint Sunum Dönüşümü" h2="Dosyaları resimlere, PDF'ye, HTML'ye ve diğer biçimlere dönüştürmek için farklı dönüştürme durumları için C# Kaynak Kodları." >}}

{{% blocks/products/pf/feature-page-summary %}}

Geliştiriciler için Microsoft<sup>®</sup> PowerPoint Sunumlarını hız ve doğrulukla dönüştürmek kolaydır. İş süreçlerini otomatikleştirmek için kısa sürede sonuçları alın. Burada, herhangi bir girişi [desteklenen PowerPoint biçimleri](https://docs.aspose.com/slides/net/supported-file-formats/) okumak veya yüklemek ve desteklenen herhangi bir çıktı biçimine yazmak veya kaydetmek için birkaç durumu tartışıyoruz. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint Dosyalarının Ara Dönüşümü" %}}
Microsoft<sup>®</sup> PowerPoint biçimlerinin karşılıklı dönüşümünü otomatikleştirmeye ihtiyaç duyulduğunda. **C# PowerPoint kitaplığı** bu hedefe ulaşmak için sınıflar sağlar. İstenen formatı yüklemek veya okumak için [Sunum sınıfını](https://apireference.aspose.com/net/slides/aspose.slides/presentation) kullanarak ve [Kaydetme yöntemini](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) çıktı dosyasını ve [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) belirterek aynı sınıfın /saveformat).OutputFormat. 
{{% blocks/products/pf/feature-page-code h3="Microsoft PowerPoint Sunumları için C# Dönüştürücü Kodu" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint'ten PDF'ye Dönüştürme" %}}

PowerPoint slaytlarını doğru bir şekilde PDF'ye dönüştürmek için Programcılar, Presentation sınıfını kullanarak belgeyi yükleyebilir ve tüm özel ve özel uygulamalar için [PdfOptions sınıfını](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) kullanabilir. metin sıkıştırma düzeyi, Jpeg kalitesi, meta dosyalarının davranışı, gizli slaytları dönüştürmenin yanı sıra belirli slaytları seçme ve daha fazlası gibi seçenekler. Hatta dönüştürülen PDF dosyasını parola ile koruma seçeneği de vardır.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint'ten PDF'ye Dönüştürücü Kodu" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint'ten HTML'ye Dönüştürme" %}}
Sunumları web sayfalarına gömmek gerektiğinde, slaytları HTML'ye dönüştürmek gerekir. API, [HtmlOptions sınıfı](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) sağlar, Gizli slaytlar gibi özel ayarlar için dosyaları yükledikten sonra kullanın, varsayılan olarak bunlar olmayacaktır. dönüştürme işlemi sırasında dahil edilmelidir. Sonlandırılmış seçenekleri dönüştürme için Kaydet yöntemine iletin.
{{% blocks/products/pf/feature-page-code h3="PowerPoint'ten HTML'ye Dönüştürme için C# Kodu" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PowerPoint Slaytlarını Görüntü Formatlarına Dönüştür" %}}
Microsoft<sup>®</sup> PowerPoint formatlarını JPEG, PNG, TIFF vb. resimlere dönüştürmek, çoğunlukla slayt küçük resimleri oluşturmak için kullanılan başka bir yaygın kullanım durumudur. Kodlama işlemi basittir. Belgeyi yükledikten sonra, her slaytta yineleme yapmak için [ISlide interface](https://apireference.aspose.com/net/slides/aspose.slides/islide) kullanın. Her yineleme sırasında, özelleştirilmiş görüntü boyutlarına sahip GetThumbnail yöntemiyle birlikte (Bitmap Nesnesi)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] öğesini kullanın. Son olarak, görüntüyü gerekli biçimde kaydedin.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint'ten Görüntü Dönüştürücü Koduna" %}}
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