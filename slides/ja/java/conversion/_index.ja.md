---
title: Javaを使用したMicrosoftPowerPointプレゼンテーションの複数ファイルへの変換
url: /ja/java/conversion/
description: Microsoft PowerPointスライドを、Javaベースのアプリケーション内でHTML、PDF、画像形式などのさまざまなファイルに変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup>Javaを介したPowerPointプレゼンテーションの変換" h2="スライドを画像、HTML、PDF、その他の形式に変換するためのさまざまな変換シナリオのJavaソースコード。" >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPointライブラリにより、Microsoft<sup>®</sup> PowerPointプレゼンテーションの変換がシンプルになり、プロセスを簡単に自動化できるようになりました。開発者は、関連するシナリオを選択し、コードを統合してアプリケーションの機能を強化できます。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointファイルの相互変換" %}}
プログラムによるMicrosoft<sup>®</sup>PowerPointファイルの相互変換は2行のコードです。 [プレゼンテーションクラス]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）を使用してファイルをロードし、出力ファイルと[SaveFormat]（https：//apireference]を持つsaveメソッドを呼び出します。 .aspose.com / slides / java / com.aspose.slides / SaveFormat）をパラメーターとして使用します。

{{% blocks/products/pf/feature-page-code h3="Java変換コード" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="PowerPointからPDFへの変換" %}}

PowerPointからPDFへの変換は、PDFファイルの大規模な共有のために一般的なケースです。手動変換の代わりに、プログラマーはそれを自動化し、PowerPointプレゼンテーションの束をPDFに変換する時間を節約できます。プレゼンテーションライブラリは、テキスト圧縮レベル、PDFコンプライアンスレベル、JPEG品質の設定、動作の定義などの特定の設定をカスタマイズするための[PdfOptionsクラス]（https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions）を提供しますメタファイルの作成、非表示のスライドの変換、選択したスライドの選択、ロックされたパスワードで保護されたPDFファイルの生成。

{{% blocks/products/pf/feature-page-code h3="JavaPowerPointからPDFへの変換コード" %}}

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


{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointからHTMLへの変換" %}}

PowerPointのスライドはWebページに直接表示されないため、変換する必要があります。プログラマーは、Presentationクラスを使用してファイルをロードし、[HtmlOptionsクラス]（https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions）を使用して特定のHTML設定を行い、saveメソッドを呼び出すことができます。

{{% blocks/products/pf/feature-page-code h3="PowerPointからHTMLへの変換用のJavaコード" %}}

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

{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointから画像への変換" %}}
Microsoft<sup>®</sup>PowerPoint形式から画像JPG、TIFF、PNGなどへの変換は、通常、スライドのサムネイルやその他の多くの場合を作成するためのものです。コーディングプロセスは簡単です。ドキュメントを読み込んだ後、[ISlideインターフェイス]（https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide）を介して各スライドを繰り返し、ISlideサムネイルISlide.getThumbnail（1f、1f）を取得します。 [BufferedImage Object]（https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html）次に、必要な画像形式で保存します。 

{{% blocks/products/pf/feature-page-code h3="JavaPowerPointから画像へのコンバーターコード" %}}
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