---
title: Преобразование презентации Microsoft PowerPoint в несколько файлов с использованием Java
url: /ru/java/conversion/
description: Преобразование слайдов Microsoft PowerPoint в различные файлы, включая HTML, PDF и форматы изображений, в приложениях на основе Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование презентаций Microsoft<sup>®</sup> PowerPoint с помощью Java" h2="Исходные коды Java для различных сценариев преобразования слайдов в изображения, HTML, PDF и другие форматы." >}}

{{% blocks/products/pf/feature-page-summary %}}

Библиотека Java PowerPoint сделала преобразование презентаций Microsoft<sup>®</sup> PowerPoint простым и легким для автоматизации процессов. Разработчики могут выбрать соответствующий сценарий и интегрировать код для расширения функциональности приложения. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Межконверсионное преобразование файлов Microsoft PowerPoint" %}}
Взаимное преобразование файлов Microsoft<sup>®</sup> PowerPoint программным путем — это всего лишь двухстрочный код. Загрузите файл с помощью [класса презентации](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) и вызовите метод сохранения с выходным файлом и [SaveFormat](https://apireference .aspose.com/slides/java/com.aspose.slides/SaveFormat) в качестве параметров.

{{% blocks/products/pf/feature-page-code h3="Код преобразования Java" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="Преобразование PowerPoint в PDF" %}}

Преобразование PowerPoint в PDF является распространенным случаем из-за огромного обмена файлами PDF. Вместо ручного преобразования программисты могут автоматизировать его и сэкономить время на кучу презентаций PowerPoint в PDF. Библиотека презентаций предоставляет [класс PdfOptions](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) для настройки определенных параметров, таких как установка уровня сжатия текста, уровня соответствия PDF, качества JPEG, определение поведения метафайлов, преобразование скрытых слайдов, выбор выбранных слайдов и создание заблокированных файлов PDF, защищенных паролем.

{{% blocks/products/pf/feature-page-code h3="Код преобразования Java PowerPoint в PDF" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft PowerPoint в HTML" %}}

Поскольку слайды PowerPoint не отображаются напрямую на веб-страницах, требуется преобразование. Программисты могут загружать файл с помощью класса Presentation, использовать [класс HtmlOptions](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) для определенных настроек HTML и вызывать метод сохранения.

{{% blocks/products/pf/feature-page-code h3="Код Java для преобразования PowerPoint в HTML" %}}

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

{{% blocks/products/pf/feature-page-section  h2="Преобразование Microsoft PowerPoint в изображения" %}}
Преобразование форматов Microsoft<sup>®</sup> PowerPoint в изображения JPG, TIFF, PNG и т. д. обычно используется для создания эскизов слайдов, а также во многих других случаях. Процесс кодирования прост. Повторите каждый слайд через [интерфейс ISlide](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) после загрузки документа, получите эскиз ISlide ISlide.getThumbnail(1f, 1f) в [Объект BufferedImage](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html), а затем сохраните изображение в требуемом формате. 

{{% blocks/products/pf/feature-page-code h3="Код конвертера Java PowerPoint в изображение" %}}
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

{{< blocks/products/pf/feature-page-options pairs="ppt-to-gif pptx-to-gif ppsm-to-jpeg potx-to-png ppsx-to-tiff pps-to-bmp pptm-to-bmp ppt-to-bmp ppt-to-word pptx-to-word svg-to-png" >}}