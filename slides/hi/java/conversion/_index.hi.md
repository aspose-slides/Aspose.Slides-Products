---
title: Microsoft PowerPoint प्रस्तुति जावा का उपयोग करके एकाधिक फ़ाइलों में रूपांतरण
url: /hi/java/conversion/
description: माइक्रोसॉफ्ट पावरपॉइंट स्लाइड्स को जावा आधारित अनुप्रयोगों के भीतर एचटीएमएल, पीडीएफ और छवि प्रारूपों सहित विभिन्न फाइलों में कनवर्ट करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> जावा के माध्यम से PowerPoint प्रस्तुति रूपांतरण" h2="विभिन्न रूपांतरण परिदृश्यों के लिए जावा स्रोत कोड स्लाइड को छवियों, एचटीएमएल, पीडीएफ और अन्य प्रारूपों में परिवर्तित करने के लिए।" >}}

{{% blocks/products/pf/feature-page-summary %}}

Java PowerPoint लाइब्रेरी ने Microsoft<sup>®</sup> PowerPoint प्रस्तुतियों के रूपांतरण को प्रक्रियाओं को स्वचालित करने के लिए सरल और आसान बना दिया है। डेवलपर्स प्रासंगिक परिदृश्य का चयन कर सकते हैं और एप्लिकेशन की कार्यक्षमता को बढ़ाने के लिए कोड को एकीकृत कर सकते हैं। 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint फ़ाइलों का अंतर रूपांतरण" %}}
प्रोग्रामेटिक रूप से Microsoft<sup>®</sup> PowerPoint फ़ाइलों का अंतर्रूपांतरण केवल दो पंक्तियों का कोड है। [प्रस्तुति वर्ग](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) का उपयोग करके फ़ाइल लोड करें और आउटपुट फ़ाइल और [SaveFormat](https://apireference) वाली सेव विधि को कॉल करें .aspose.com/slides/java/com.aspose.slides/SaveFormat) पैरामीटर के रूप में।

{{% blocks/products/pf/feature-page-code h3="जावा रूपांतरण कोड" %}}

```cs
// Load source file
Presentation interConvert = new Presentation("sourceFile.ppt");

// save the file in relevant format
interConvert.save("output.pptx", SaveFormat.Pptx);   
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pptx pptx-to-ppt potm-to-pptm potx-to-pot ppsm-to-ppsx ppt-to-word pptx-to-word svg-to-png" >}}


{{% blocks/products/pf/feature-page-section  h2="पावरपॉइंट से पीडीएफ रूपांतरण" %}}

पीडीएफ फाइलों के विशाल साझाकरण के कारण पावरपॉइंट से पीडीएफ रूपांतरण एक सामान्य मामला है। मैन्युअल रूपांतरणों के बजाय, प्रोग्रामर इसे स्वचालित कर सकते हैं और पीडीएफ में पावरपॉइंट प्रस्तुतियों के समूह के लिए समय बचा सकते हैं। प्रस्तुति पुस्तकालय विशिष्ट सेटिंग्स को अनुकूलित करने के लिए [PdfOptions class](https://apireference.aspose.com/java/slides/com.aspose.slides/PdfOptions) प्रदान करता है जैसे पाठ संपीड़न स्तर, PDF अनुपालन स्तर, JPEG गुणवत्ता, व्यवहार को परिभाषित करना मेटाफ़ाइल्स, छिपी हुई स्लाइड्स को परिवर्तित करना, चयनित स्लाइड्स को चुनना और लॉक पासवर्ड से सुरक्षित पीडीएफ फाइलों को उत्पन्न करना।

{{% blocks/products/pf/feature-page-code h3="जावा पावरपॉइंट से पीडीएफ रूपांतरण कोड" %}}

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


{{% blocks/products/pf/feature-page-section  h2="Microsoft PowerPoint से HTML रूपांतरण" %}}

चूंकि PowerPoint स्लाइड सीधे वेबपृष्ठों पर प्रदर्शित नहीं होती हैं, इसलिए रूपांतरण की आवश्यकता होती है। प्रोग्रामर प्रेजेंटेशन क्लास का उपयोग करके फ़ाइल लोड कर सकते हैं, विशिष्ट HTML सेटिंग्स के लिए [HtmlOptions class](https://apireference.aspose.com/slides/java/com.aspose.slides/HtmlOptions) का उपयोग कर सकते हैं और सेव विधि को लागू कर सकते हैं।

{{% blocks/products/pf/feature-page-code h3="PowerPoint से HTML रूपांतरण के लिए जावा कोड" %}}

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

{{% blocks/products/pf/feature-page-section  h2="छवियाँ रूपांतरण के लिए Microsoft PowerPoint" %}}
Microsoft<sup>®</sup> PowerPoint प्रारूप छवियों के लिए JPG, TIFF, PNG, आदि रूपांतरण सामान्य रूप से स्लाइड थंबनेल बनाने के साथ-साथ बहुत अधिक मामलों के लिए है। कोडिंग प्रक्रिया सरल है। दस्तावेज़ लोड करने के बाद [ISlide इंटरफ़ेस](https://apireference.aspose.com/slides/java/com.aspose.slides/ISlide) के माध्यम से प्रत्येक स्लाइड के माध्यम से पुनरावृति करें, ISlide थंबनेल ISlide.getThumbnail(1f, 1f) प्राप्त करें [बफर्डइमेज ऑब्जेक्ट](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html) और फिर आवश्यक इमेज फॉर्मेट में सेव करें। 

{{% blocks/products/pf/feature-page-code h3="जावा पावरपॉइंट टू इमेज कन्वर्टर कोड" %}}
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