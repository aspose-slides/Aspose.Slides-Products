---
title: C＃を使用したMicrosoftPowerPointプレゼンテーションの複数ファイルへの変換
url: /ja/net/conversion/
description: Microsoft PowerPointスライドを、.NET Framework、.NET Core、Windows Azure、Mono、またはXamarinプラットフォーム上のPDF、HTML、および画像形式を含むさまざまなファイルに変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup>C＃によるPowerPointプレゼンテーション変換" h2="ファイルを画像、PDF、HTML、その他の形式に変換するためのさまざまな変換ケースのC＃ソースコード。" >}}

{{% blocks/products/pf/feature-page-summary %}}

開発者は、Microsoft<sup>®</sup>のPowerPointプレゼンテーションを迅速かつ正確に変換するのは簡単です。ビジネスプロセスを自動化するために、すぐに結果を取得します。ここでは、入力[サポートされているPowerPoint形式]（https://docs.aspose.com/slides/net/supported-file-formats/）を読み取ったりロードしたり、サポートされている出力形式に書き込んだり保存したりするいくつかのケースについて説明します。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointファイルの相互変換" %}}
Microsoft<sup>®</sup>PowerPoint形式の相互変換を自動化する必要があるときはいつでも。 ** C＃PowerPointライブラリ**は、この目標を達成するためのクラスを提供します。 [プレゼンテーションクラス]（https://apireference.aspose.com/net/slides/aspose.slides/presentation）を使用してファイルをロードし、目的の形式をロードまたは読み取り、[保存メソッド]（https：//apireference。出力ファイルと[SaveFormat]（https://apireference.aspose.com/slides/net/aspose.slides.export）を指定して、同じクラスのaspose.com/slides/net/aspose.slides/presentation/methods/save） /saveformat).OutputFormat。 
{{% blocks/products/pf/feature-page-code h3="Microsoft PowerPointプレゼンテーション用のC＃コンバーターコード" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C＃PowerPointからPDFへの変換" %}}

PowerPointスライドをPDFに正確に変換するために、プログラマーはPresentationクラスを使用してドキュメントをロードし、すべての特定のカスタムに[PdfOptionsクラス]（https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions）を使用できます。テキスト圧縮レベル、Jpeg品質、メタファイルの動作、非表示のスライドの変換、特定のスライドの選択などのオプション。変換されたPDFファイルをパスワードで保護するオプションもあります。
{{% blocks/products/pf/feature-page-code h3="C＃PowerPointからPDFへのコンバーターコード" %}}

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


{{% blocks/products/pf/feature-page-section  h2="MicrosoftPowerPointからHTMLへの変換" %}}
Webページ内にプレゼンテーションを埋め込む必要がある場合は常に、スライドをHTMLに変換する必要があります。 APIは[HtmlOptionsクラス]（https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions）を提供します。ファイルを読み込んだ後、非表示のスライドなどの特別な設定に使用します。デフォルトでは、これらは使用されません。変換プロセス中に含まれます。完成したオプションを変換のためにSaveメソッドに渡します。
{{% blocks/products/pf/feature-page-code h3="PowerPointからHTMLへの変換のためのC＃コード" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PowerPointスライドを画像形式に変換する" %}}
Microsoft<sup>®</sup>PowerPoint形式を画像に変換するJPEG、PNG、TIFFなどは、スライドのサムネイルを作成するために主に使用されるもう1つの一般的な使用例です。コーディングプロセスは簡単です。ドキュメントを読み込んだ後、[ISlideインターフェイス]（https://apireference.aspose.com/net/slides/aspose.slides/islide）を使用して各スライドを繰り返し処理します。各反復中に、（ビットマップオブジェクト）[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8]を、カスタマイズされた画像サイズを持つGetThumbnailメソッドとともに使用します。最後に、必要な形式で画像を保存します。
{{% blocks/products/pf/feature-page-code h3="C＃PowerPointから画像へのコンバーターコード" %}}
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