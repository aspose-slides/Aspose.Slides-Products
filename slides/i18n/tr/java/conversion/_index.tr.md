---
title: Java kullanarak Microsoft PowerPoint Sunumunu Birden Çok Dosyaya Dönüştürme
url: /tr/java/conversion/
description: Microsoft PowerPoint Slaytlarını, Java tabanlı uygulamalarda HTML, PDF ve görüntü formatları dahil olmak üzere farklı dosyalara dönüştürün.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java ile Microsoft<sup>®</sup> PowerPoint Sunum Dönüştürme" h2="Slaytları resimlere, HTML'ye, PDF'ye ve diğer biçimlere dönüştürmek için çeşitli dönüştürme senaryoları için Java kaynak kodları." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint kitaplığı, Microsoft<sup>®</sup> PowerPoint Sunumlarının dönüşümünü basit ve süreçleri otomatikleştirmesi kolay hale getirdi. Geliştiriciler, uygulama işlevselliğini geliştirmek için ilgili senaryoyu seçebilir ve kodu entegre edebilir. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint Dosyalarının Ara Dönüşümü" %}}
Microsoft<sup>®</sup> PowerPoint dosyalarının program aracılığıyla birbirine dönüştürülmesi yalnızca iki satırlık bir koddur. [Sunum sınıfını](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) kullanarak dosyayı yükleyin ve çıktı dosyasına ve [SaveFormat](https://apireference) içeren kaydetme yöntemini çağırın .aspose.com/slides/java/com.aspose.slides/SaveFormat) parametre olarak.

{{% blocks/products/pf/feature-page-code h3="Java Dönüşüm Kodu" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint'ten PDF'ye Dönüştürme" %}}

PowerPoint'ten PDF'ye dönüştürme, PDF dosyalarının büyük paylaşımı nedeniyle yaygın bir durumdur. Programcılar manuel dönüştürmeler yerine bunu otomatikleştirebilir ve bir sürü PowerPoint sunumunu PDF'ye dönüştürmek için zamandan tasarruf edebilir. Sunum kitaplığı, metin sıkıştırma düzeyi, PDF uyumluluk düzeyi, JPEG kalitesi gibi belirli ayarları özelleştirmek için [PdfOptions sınıfı](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) sağlar, davranışı tanımlayın meta dosyaları, gizli slaytları dönüştürme, seçilen slaytları seçme ve kilitli parola korumalı PDF dosyaları oluşturma.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint'ten PDF'ye Dönüştürme Kodu" %}}

```cs
// Load file
Presentation powerpointopdf = new Presentation("srcFile.pptx");

// Create PdfOptions class object
PdfOptions slidetopdfOpt = new PdfOptions();
               
// Set JPEG Quality
slidetopdfOpt.setJpegQuality((byte) 90);

// Define behavior for Metafiles
slidetopdfOpt.setSaveMetafilesAsPng(true);

// Set Text Compression level
slidetopdfOpt.setTextCompression(PdfTextCompression.Flate);

// Define the PDF standard
slidetopdfOpt.setCompliance(PdfCompliance.Pdf15);
              
INotesCommentsLayoutingOptions options = slidetopdfOpt.getNotesCommentsLayouting();
options.setNotesPosition(NotesPositions.BottomFull);

// Specify that the generated document should include hidden slides
slidetopdfOpt.setShowHiddenSlides(true);
	
// Setting PDF password
slidetopdfOpt.setPassword("password");	

// Save the presentation to PDF with specified options
powerpointopdf.save("java-powerpoint-to.pdf", SaveFormat.Pdf, slidetopdfOpt);


// Setting array of slides positions
// int[] slides = new int[] { 2, 3, 5 };

// Save the presentation to PDF
// powerpointopdf.save("java-powerpoint-to.pdf", slides, SaveFormat.Pdf);

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint'ten HTML'ye Dönüştürme" %}}

PowerPoint slaytları doğrudan web sayfalarında görüntülenmediğinden dönüştürme ihtiyacı vardır. Programcılar, Presentation sınıfını kullanarak dosya yükleyebilir, belirli HTML ayarları için [HtmlOptions sınıfını](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) kullanabilir ve kaydetme yöntemini çağırabilir.

{{% blocks/products/pf/feature-page-code h3="PowerPoint'ten HTML'ye Dönüştürme için Java kodu" %}}

```cs

// Load the file
Presentation powerpointohtml = new Presentation("srcFile.pptx");

// Create HTML options
HtmlOptions pptxhtmlOpt = new HtmlOptions();

// Displaying hidden slides
pptxhtmlOpt.setShowHiddenSlides(true);

// Save the PPTX as HTML
powerpointohtml.save("java-powerpoint-to.html", SaveFormat.Html, pptxhtmlOpt); 

```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint'ten Görüntülere Dönüştürme" %}}
Microsoft<sup>®</sup> PowerPoint biçimlerinden görüntülere JPG, TIFF, PNG, vb. dönüştürme normalde slaytların küçük resimlerinin yanı sıra çok daha fazla durum oluşturmak içindir. Kodlama işlemi basittir. Belgeyi yükledikten sonra [ISlide interface](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) aracılığıyla her slaytta yineleyin, ISlide küçük resmini ISlide.getThumbnail(1f, 1f) içine alın [BufferedImage Object](https://docs.Oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) ve ardından gerekli görüntü formatında kaydedin. 

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint'ten Görüntü Dönüştürücü Koduna" %}}
```cs
// Load the PowerPoint document
Presentation PowerPointtoImage = new Presentation("templatefile.pptx");


// for generating a full scale image
// BufferedImage bi = sld.getThumbnail(1f, 1f);

// for Customized dimensions, define dimensions
int finalX = 1200;
int finalY = 800;

// Get scaled values of X and Y
float DimensionX = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getWidth()) * finalX;
float DimensionY = (float)(1.0 / PowerPointtoImage.getSlideSize().getSize().getHeight()) * finalY;

// Loop through each slide in the presentation
for (ISlide sld : PowerPointtoImage.getSlides()) {
	
// Create a full scale image
BufferedImage bi = sld.getThumbnail(DimensionX, DimensionY);

// Create a new file
File outputfile = new File(sld.getSlideNumber() + "_Slide.jpg");
	
// Save the image to disk in JPEG format
ImageIO.write(bi, "jpg", outputfile);
}
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp" >}}