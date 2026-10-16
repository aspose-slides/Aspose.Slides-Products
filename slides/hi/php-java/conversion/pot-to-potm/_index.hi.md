---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP में POT को POTM में बदलें
weight: 940
url: /hi/php-java/conversion/pot-to-potm/ 
keywords: "Convert, PowerPoint, POT, POTM, Presentation, PHP"
description: POT से POTM PHP रूपांतरण के लिए नमूना कोड। POT फ़ाइलों को POTM फ़ाइलों में बैच रूपांतरण के लिए PowerPoint PHP API का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP में POT को POTM में बदलें" h2="POT को POTM में बदलने के लिए शक्तिशाली पावरपॉइंट PHP लाइब्रेरी"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP में POT को POTM में बदलें" %}}

प्रोग्राम के रूप में POT फ़ाइलों को POTM में कनवर्ट करने की आवश्यकता है? [*Aspose.Slides for PHP by Java*](https://products.aspose.com/slides/hi/php-java/) का उपयोग करके कोई भी डेवलपर PHP कोड की कुछ पंक्तियों के साथ POT को POTM फ़ॉर्मैट में बदल सकता है .

एक आधुनिक प्रेजेंटेशन प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for PHP POT से POTM जल्दी से बनाता है। सीधे अपने [ब्राउज़र](https://products.aspose.app/slides/conversion) में POT से POTM रूपांतरण की गुणवत्ता का परीक्षण करें। Aspose PowerPoint PPTX लाइब्रेरी आपको POT फाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न आदेश का उपयोग करके [संगीतकार](https://packagist.org/packages/aspose/slides) से पुस्तकालय स्थापित कर सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कंसोल/टर्मिनल" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP में POT को POTM के रूप में सेव करें" %}}

POT से POTM रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए निःशुल्क ऐप का उपयोग करें।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड POT से POTM PHP रूपांतरण दिखाता है" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.pot");
try
{
    $pres->save("output.potm", SaveFormat::Potm);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{< blocks/products/pf/slides-design-update-10-2026/pair >}}
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP में POT को POTM में कैसे बदलें" intro="PHP का उपयोग करके POT फ़ाइल को POTM में बदलने के लिए ये चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ POT फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat को निर्दिष्ट करते समय `सेव` विधि को कॉल करें। POTM पैरामीटर के रूप में{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}POT फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="सिस्टम आवश्यकताएं" intro="PHP रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7 स्थापित करें, PHP को सिस्टम `PATH` चर में पथ जोड़ें और `php.ini` फ़ाइल में `allow_url_include` को `चालू` पर सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE 8 स्थापित करें। `JAVA_HOME` पर्यावरण चर को स्थापित JRE स्थान के पथ के रूप में सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपाचे टॉमकैट 8.0 स्थापित करें (देखें [अधिक](https://docs.aspose.com/slides/php-java/installation/))।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert POT to POTM"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप POT को कई अन्य फ़ाइल स्वरूपों में भी बदल सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-bmp/" name="POT TO BMP" description="बिटमैप चित्र" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-fodp/" name="POT TO FODP" description="ओपन डॉक्यूमेंट फ्लैट एक्सएमएल प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-gif/" name="POT TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-html/" name="POT TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-jpg/" name="POT TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-odp/" name="POT TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-otp/" name="POT TO OTP" description="OpenDocument मानक प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-pdf/" name="POT TO PDF" description="संवहन दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-png/" name="POT TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-potx/" name="POT TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-pps/" name="POT TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-ppsm/" name="POT TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-ppsx/" name="POT TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-ppt/" name="POT TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-pptm/" name="POT TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-pptx/" name="POT TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-svg/" name="POT TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-swf/" name="POT TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-tiff/" name="POT TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/pot-to-xps/" name="POT TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
