---
title: C#을 사용하여 여러 파일로 Microsoft PowerPoint 프레젠테이션 변환
url: /ko/net/conversion/
description: Microsoft PowerPoint Slides를 .NET Framework, .NET Core, Windows Azure, Mono 또는 Xamarin 플랫폼에서 PDF, HTML 및 이미지 형식을 포함한 다양한 파일로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을 통한 Microsoft<sup>®</sup> PowerPoint 프레젠테이션 변환" h2="파일을 이미지, PDF, HTML 및 기타 형식으로 변환하는 다양한 변환 사례에 대한 C# 소스 코드." >}}

{{% blocks/products/pf/feature-page-summary %}}

개발자는 Microsoft<sup>®</sup> PowerPoint 프레젠테이션을 빠르고 정확하게 변환할 수 있습니다. 비즈니스 프로세스를 자동화하기 위해 짧은 시간 안에 결과를 얻으십시오. 여기서는 입력[지원되는 PowerPoint 형식](https://docs.aspose.com/slides/net/supported-file-formats/)을 읽거나 로드하고 지원되는 출력 형식으로 쓰거나 저장하는 몇 가지 경우에 대해 논의하고 있습니다. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint 파일의 상호 변환" %}}
Microsoft<sup>®</sup> PowerPoint 형식의 상호 변환을 자동화해야 할 때마다. **C# PowerPoint 라이브러리**는 이 목표를 달성하기 위한 클래스를 제공합니다. [Presentation class](https://apireference.aspose.com/net/slides/aspose.slides/presentation)를 사용하여 파일을 불러와 원하는 형식을 불러오거나 읽어 들인 후 [Save method](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) 출력 파일 지정 및 [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) /저장 형식).출력 형식. 
{{% blocks/products/pf/feature-page-code h3="Microsoft PowerPoint 프레젠테이션용 C# 변환기 코드" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx" >}}


{{% blocks/products/pf/feature-page-section  h2="C# PowerPoint에서 PDF로 변환" %}}

PowerPoint 슬라이드를 PDF로 정확하게 변환하기 위해 프로그래머는 프레젠테이션 클래스를 사용하여 문서를 로드하고 모든 특정 및 사용자 정의에 대해 [PdfOptions 클래스](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions)를 사용할 수 있습니다. 텍스트 압축 수준, JPEG 품질, 메타파일 동작, 숨겨진 슬라이드 변환, 특정 슬라이드 선택 등의 옵션이 있습니다. 변환된 PDF 파일을 암호로 보호하는 옵션도 있습니다.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint에서 PDF 변환기 코드로" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint에서 HTML로 변환" %}}
웹 페이지 내에 프레젠테이션을 포함해야 하는 경우 슬라이드를 HTML로 변환해야 합니다. API는 [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions)를 제공하며, 기본적으로 숨겨진 슬라이드와 같은 특수 설정을 위해 파일을 로드한 후 사용합니다. 변환 프로세스 중에 포함됩니다. 변환을 위해 최종 옵션을 Save 메서드에 전달합니다.
{{% blocks/products/pf/feature-page-code h3="PowerPoint에서 HTML로 변환하는 C# 코드" %}}

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

{{% blocks/products/pf/feature-page-section  h2="PowerPoint 슬라이드를 이미지 형식으로 변환" %}}
Microsoft<sup>®</sup> PowerPoint 형식을 JPEG, PNG, TIFF 등의 이미지로 변환하는 것은 슬라이드 축소판을 만드는 데 주로 사용되는 또 다른 일반적인 사용 사례입니다. 코딩 과정은 간단합니다. 문서를 로드한 후 [ISlide 인터페이스](https://apireference.aspose.com/net/slides/aspose.slides/islide)를 사용하여 각 슬라이드를 반복합니다. 각 반복 중에 (Bitmap Object)[https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8]를 사용자 정의된 이미지 크기가 있는 GetThumbnail 메소드와 함께 사용하십시오. 마지막으로 필요한 형식으로 이미지를 저장합니다.
{{% blocks/products/pf/feature-page-code h3="C# PowerPoint를 이미지 변환기 코드로" %}}
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