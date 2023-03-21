---
title: Java를 사용하여 여러 파일로 Microsoft PowerPoint 프레젠테이션 변환
url: /ko/java/conversion/
description: Microsoft PowerPoint 슬라이드를 Java 기반 응용 프로그램 내에서 HTML, PDF 및 이미지 형식을 포함한 다양한 파일로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통한 Microsoft<sup>®</sup> PowerPoint 프레젠테이션 변환" h2="슬라이드를 이미지, HTML, PDF 및 기타 형식으로 변환하는 다양한 변환 시나리오용 Java 소스 코드." >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint 라이브러리를 사용하면 Microsoft<sup>®</sup> PowerPoint 프레젠테이션을 간단하고 쉽게 자동화할 수 있습니다. 개발자는 관련 시나리오를 선택하고 코드를 통합하여 애플리케이션 기능을 향상시킬 수 있습니다. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 파일의 상호 변환" %}}
프로그래밍 방식으로 Microsoft<sup>®</sup> PowerPoint 파일을 상호 변환하는 것은 단 두 줄의 코드입니다. [Presentation 클래스](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)를 사용하여 파일을 로드하고 출력 파일과 [SaveFormat](https://apireference)이 있는 save 메소드를 호출합니다. .aspose.com/slides/java/com.aspose.slides/SaveFormat)을 매개변수로 사용합니다.

{{% blocks/products/pf/feature-page-code h3="자바 변환 코드" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPoint에서 PDF로 변환" %}}

PowerPoint에서 PDF로의 변환은 PDF 파일의 거대한 공유로 인해 일반적인 경우입니다. 프로그래머는 수동 변환 대신 이를 자동화하고 여러 PowerPoint 프레젠테이션을 PDF로 만드는 시간을 절약할 수 있습니다. 프레젠테이션 라이브러리는 텍스트 압축 수준, PDF 준수 수준, JPEG 품질 설정, 동작 정의와 같은 특정 설정을 사용자 지정하기 위한 [PdfOptions 클래스](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions)를 제공합니다. 메타 파일, 숨겨진 슬라이드 변환, 선택한 슬라이드 선택 및 잠긴 암호로 보호된 PDF 파일 생성.

{{% blocks/products/pf/feature-page-code h3="Java PowerPoint에서 PDF로의 변환 코드" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint에서 HTML로 변환" %}}

PowerPoint 슬라이드는 웹 페이지에 직접 표시되지 않으므로 변환이 필요합니다. 프로그래머는 Presentation 클래스를 사용하여 파일을 로드하고 특정 HTML 설정에 대해 [HtmlOptions 클래스](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions)를 활용하고 save 메소드를 호출할 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="PowerPoint에서 HTML로 변환하는 Java 코드" %}}

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

{{% blocks/products/pf/feature-page-section  h2="마이크로소프트 파워포인트를 이미지로 변환" %}}
Microsoft<sup>®</sup> PowerPoint 형식을 이미지 JPG, TIFF, PNG 등으로 변환하는 것은 일반적으로 훨씬 더 많은 경우뿐 아니라 슬라이드 축소판을 만들기 위한 것입니다. 코딩 과정은 간단합니다. 문서를 로드한 후 [ISlide 인터페이스](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide)를 통해 각 슬라이드를 반복하고 ISlide 축소판 ISlide.getThumbnail(1f, 1f)을 가져옵니다. [BufferedImage Object](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) 후 필요한 이미지 형식으로 저장합니다. 

{{% blocks/products/pf/feature-page-code h3="자바 파워포인트를 이미지 변환기 코드로" %}}
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