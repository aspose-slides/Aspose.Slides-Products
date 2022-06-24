---
title: माइक्रोसॉफ्ट पावरपॉइंट प्रेजेंटेशन PHP में पीडीएफ में रूपांतरण
url: /hi/php-java/conversion/
keywords: "Convert, PowerPoint, Presentation, PHP, PDF, Convert to PDF, PPT to PDF"
description: पीपीटी को पीडीएफ में बदलने के लिए पीएचपी एपीआई। पीएचपी में प्रस्तुतियों को जेपीजी, पीएनजी और अन्य प्रारूपों में कनवर्ट करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Microsoft<sup>®</sup> PHP में पीडीएफ रूपांतरण के लिए PowerPoint प्रस्तुति" h2="पीपीटी को पीडीएफ, पीएनजी, एचटीएमएल, जेपीईजी, पीपीटीएक्स और अन्य प्रारूपों में बदलने के लिए विभिन्न रूपांतरण मामलों के लिए पीएचपी स्रोत कोड।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[जावा के माध्यम से PHP के लिए Aspose.Slides](https://products.aspose.com/slides/hi/php-java/) एक शक्तिशाली ऑन-प्रिमाइसेस क्लास लाइब्रेरी है जिसका उपयोग प्रस्तुतियों के साथ प्रसंस्करण और काम करने के लिए किया जाता है। डेवलपर्स के लिए गति और सटीकता के साथ पावरपॉइंट को पीडीएफ में बदलना आसान है। व्यावसायिक प्रक्रियाओं को स्वचालित करने के लिए कुछ ही समय में परिणाम प्राप्त करें। हम यहां किसी इनपुट को पढ़ने या लोड करने के कुछ मामलों पर चर्चा कर रहे हैं [समर्थित पावरपॉइंट प्रारूप](https://docs.aspose.com/slides/php-java/supported-file-formats/) और किसी भी समर्थित आउटपुट स्वरूप में लिखने या सहेजने के लिए . 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PHP में PowerPoint से PDF रूपांतरण" %}}
[Aspose.Slides](https://products.aspose.com/slides/hi/php-java/) आपको PowerPoint PPT, PPTX, और OpenOffice ODP प्रारूपों में फ़ाइलों को PDF में बदलने की अनुमति देता है। किसी प्रस्तुति को PDF में बदलने के लिए, बस फ़ाइल का नाम पास करें और प्रारूप को `Presentation.save` विधि में सहेजें। `प्रस्तुति` वर्ग `सेव` विधि को उजागर करता है जिसे संपूर्ण पीपीटी, पीपीटीएक्स, या ओडीपी प्रस्तुति को एक पीडीएफ दस्तावेज़ में बदलने के लिए कहा जा सकता है।

{{% blocks/products/pf/feature-page-code h3="पीएचपी पावरपॉइंट से पीडीएफ रूपांतरण" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $pres->save("output.pdf", SaveFormat::Pdf); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf potm-to-pdf potx-to-pdf ppsm-to-pdf odp-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="पीएचपी में पीपीटी रूपांतरण के लिए पीडीएफ" %}}
[Aspose.Slides](https://products.aspose.com/slides/hi/php-java/) से आप PDF से प्रस्तुतीकरण आयात कर सकते हैं। अनिवार्य रूप से, आपको एक पीडीएफ को पावरपॉइंट प्रेजेंटेशन में बदलने के लिए मिलता है। पीडीएफ को पावरपॉइंट में बदलने के लिए, इन चरणों का पालन करें:
- `प्रस्तुति` वर्ग की किसी वस्तु को त्वरित करें।
- `addFromPdf` विधि को कॉल करें और पीडीएफ फाइल पास करें।
- फ़ाइल को PowerPoint प्रारूप में सहेजने के लिए `सहेजें` विधि का उपयोग करें।

{{% blocks/products/pf/feature-page-code h3="PHP पीडीएफ से पावरपॉइंट रूपांतरण" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("output.pptx", SaveFormat::Pptx); 
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-ppt pdf-to-pptx pdf-to-odp pdf-to-png pdf-to-jpg pdf-to-html" >}}


{{% blocks/products/pf/feature-page-section  h2="पीएचपी में कस्टम विकल्पों के साथ पीपीटी को पीडीएफ में बदलें" %}}

पावरपॉइंट स्लाइड्स को पीडीएफ में सटीक रूप से परिवर्तित करने के लिए, प्रोग्रामर `प्रेजेंटेशन` क्लास का उपयोग करके दस्तावेज़ को लोड कर सकते हैं और टेक्स्ट कंप्रेशन स्तर, जेपीईजी गुणवत्ता, मेटाफाइल्स के व्यवहार, छिपी हुई स्लाइड्स को बदलने के साथ-साथ चयन करने के लिए सभी विशिष्ट और कस्टम विकल्पों के लिए `पीडीएफऑप्शन` क्लास का उपयोग कर सकते हैं। विशिष्ट स्लाइड और बहुत कुछ। यहां तक ​​कि परिवर्तित पीडीएफ फाइल को पासवर्ड से सुरक्षित रखने का विकल्प भी है।
{{% blocks/products/pf/feature-page-code h3="कस्टम सेटिंग्स के साथ पीएचपी पावरपॉइंट से पीडीएफ रूपांतरण" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\PdfOptions;
use aspose\slides\PdfTextCompression;
use aspose\slides\PdfCompliance;
 
$pres = new Presentation("input.pptx");
try
{
    $pdfOptions = new PdfOptions();
    $pdfOptions->setJpegQuality(90);
    $pdfOptions->setSaveMetafilesAsPng(true);
    $pdfOptions->setTextCompression(PdfTextCompression::Flate);
    $pdfOptions->setCompliance(PdfCompliance::Pdf15);
    $pres->save("output.pdf", SaveFormat::Pdf, $pdfOptions);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="ppt-to-pdf pptx-to-pdf ppsm-to-pdf potx-to-pdf ppsx-to-pdf pps-to-pdf pptm-to-pdf" >}}


{{% blocks/products/pf/feature-page-section  h2="PHP में Microsoft PowerPoint से HTML रूपांतरण" %}}
जब कभी वेबपेजों के भीतर प्रस्तुतियों को एम्बेड करने की आवश्यकता होती है, तो स्लाइड्स को HTML में बदलने की आवश्यकता होती है। 
{{% blocks/products/pf/feature-page-code h3="PowerPoint से HTML रूपांतरण के लिए PHP कोड" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
use aspose\slides\Html5Options;
 
$pres = new Presentation("input.pptx");
try
{
    $html5Options = new Html5Options();
    $html5Options->setAnimateShapes(false);
    $html5Options->setAnimateTransitions(false);
    $pres->save("output.html", SaveFormat::Html5, $html5Options);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-html pptx-to-html ppsm-to-html potx-to-html ppsx-to-html pps-to-html pptm-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="PowerPoint को JPG में बदलें" %}}
Microsoft<sup>®</sup> PowerPoint प्रारूपों को JPEG, PNG, TIFF आदि छवियों में परिवर्तित करना एक अन्य सामान्य उपयोग का मामला है जिसका उपयोग ज्यादातर स्लाइड थंबनेल बनाने के लिए किया जाता है। 
{{% blocks/products/pf/feature-page-code h3="PHP पीपीटी से जेपीजी कनवर्टर कोड" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
 
$pres = new Presentation("input.pptx");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(1, 1);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".jpg");
        $imageio->write($bmp, "JPEG", $javafile);
    }
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>  
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ppt-to-jpg pptx-to-jpg ppt-to-png pptx-to-png ppt-to-gif pptx-to-gif" >}}