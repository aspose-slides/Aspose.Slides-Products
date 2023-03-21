---
title: माइक्रोसॉफ्ट पावरपॉइंट प्रेजेंटेशन सी # का उपयोग कर एकाधिक फाइलों में रूपांतरण
url: /hi/net/conversion/
description: Microsoft PowerPoint स्लाइड को .NET Framework, .NET Core, Windows Azure, Mono या Xamarin प्लेटफ़ॉर्म पर PDF, HTML और छवि स्वरूपों सहित विभिन्न फ़ाइलों में कनवर्ट करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> C# के माध्यम से PowerPoint प्रस्तुति रूपांतरण" h2="सी # विभिन्न रूपांतरण मामलों के लिए स्रोत कोड फ़ाइलों को छवियों, पीडीएफ, एचटीएमएल और अन्य प्रारूपों में परिवर्तित करने के लिए।" >}}

{{% blocks/products/pf/feature-page-summary %}}

डेवलपर्स के लिए Microsoft<sup>®</sup> PowerPoint प्रस्तुतियों को गति और सटीकता के साथ रूपांतरित करना आसान है। व्यावसायिक प्रक्रियाओं को स्वचालित करने के लिए कुछ ही समय में परिणाम प्राप्त करें। हम यहां किसी इनपुट को पढ़ने या लोड करने के कुछ मामलों पर चर्चा कर रहे हैं [समर्थित पावरपॉइंट प्रारूप](https://docs.aspose.com/slides/net/supported-file-formats/) और किसी भी समर्थित आउटपुट स्वरूप में लिखने या सहेजने के लिए। 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint फ़ाइलों का अंतर रूपांतरण" %}}
जब भी Microsoft<sup>®</sup> PowerPoint प्रारूपों के अंतर रूपांतरण को स्वचालित करने की आवश्यकता होती है। **C# PowerPoint लाइब्रेरी** इस लक्ष्य को प्राप्त करने के लिए कक्षाएं प्रदान करती है। वांछित प्रारूप को लोड करने या पढ़ने के लिए [प्रस्तुति वर्ग](https://apireference.aspose.com/net/slides/aspose.slides/presentation) का उपयोग करके फ़ाइल लोड करें और [सेव मेथड](https://apireference. aspose.com/slides/net/aspose.slides/presentation/methods/save) आउटपुट फ़ाइल और [SaveFormat](https://apireference.aspose.com/slides/net/aspose.slides.export) को निर्दिष्ट करके उसी वर्ग के /सेवफॉर्मेट)।आउटपुटफॉर्मेट। 
{{% blocks/products/pf/feature-page-code h3="Microsoft PowerPoint प्रस्तुतियों के लिए C# कनवर्टर कोड" %}}

```cs
// Load the Source File
var pptToPptx = new Presentation("sourceFile.ppt");
// Save into the desired format
pptToPptx.Save("powerpoiont-inter-conversion.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="सी # पावरपॉइंट से पीडीएफ रूपांतरण" %}}

PowerPoint स्लाइड्स को PDF में सटीक रूप से परिवर्तित करने के लिए, प्रोग्रामर प्रेजेंटेशन क्लास का उपयोग करके दस्तावेज़ को लोड कर सकते हैं और सभी विशिष्ट और कस्टम के लिए [PdfOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/pdfoptions) का उपयोग कर सकते हैं। टेक्स्ट कम्प्रेशन लेवल, जेपीईजी क्वालिटी, मेटाफाइल्स का बिहेवियर, हिडन स्लाइड्स को कन्वर्ट करने के साथ-साथ विशिष्ट स्लाइड्स का चयन करने जैसे विकल्प। यहां तक ​​कि परिवर्तित पीडीएफ फाइल को पासवर्ड से सुरक्षित रखने का विकल्प भी है।
{{% blocks/products/pf/feature-page-code h3="सी # पावरपॉइंट से पीडीएफ कन्वर्टर कोड" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint से HTML रूपांतरण" %}}
जब कभी वेबपेजों के भीतर प्रस्तुतियों को एम्बेड करने की आवश्यकता होती है, तो स्लाइड्स को HTML में बदलने की आवश्यकता होती है। एपीआई [HtmlOptions class](https://apireference.aspose.com/slides/net/aspose.slides.export/htmloptions) प्रदान करता है, विशेष सेटिंग्स जैसे हिडन स्लाइड्स के लिए फाइल लोड करने के बाद इसका उपयोग करें, डिफ़ॉल्ट रूप से, ये नहीं होंगे रूपांतरण प्रक्रिया के दौरान शामिल किया जाएगा। रूपांतरण के लिए विधि सहेजें के लिए अंतिम विकल्प पास करें।
{{% blocks/products/pf/feature-page-code h3="पावरपॉइंट से एचटीएमएल रूपांतरण के लिए सी # कोड" %}}

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

{{% blocks/products/pf/feature-page-section  h2="पावरपॉइंट स्लाइड्स को इमेज फॉर्मेट में बदलें" %}}
Microsoft<sup>®</sup> PowerPoint प्रारूपों को JPEG, PNG, TIFF आदि छवियों में परिवर्तित करना एक अन्य सामान्य उपयोग का मामला है जिसका उपयोग ज्यादातर स्लाइड थंबनेल बनाने के लिए किया जाता है। कोडिंग प्रक्रिया सरल है। दस्तावेज़ लोड करने के बाद, प्रत्येक स्लाइड के माध्यम से पुनरावृति करने के लिए [ISlide इंटरफ़ेस](https://apireference.aspose.com/net/slides/aspose.slides/islide) का उपयोग करें। प्रत्येक पुनरावृत्ति के दौरान, (बिटमैप ऑब्जेक्ट) [https://docs.microsoft.com/en-us/dotnet/api/system.drawing.bitmap?view=netframework-4.8] का उपयोग इसके GetThumbnail mehtod के साथ अनुकूलित छवि आयामों के साथ करें। अंत में छवि को आवश्यक प्रारूप में सहेजें।
{{% blocks/products/pf/feature-page-code h3="सी # पावरपॉइंट टू इमेज कन्वर्टर कोड" %}}
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