---
lastmod: 2026-08-11
locales: "ar,cs,de,el,es,fa,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant"
title: PHP में OTP को BMP में बदलें
weight: 430
url: /hi/php-java/conversion/otp-to-bmp/ 
keywords: "Convert, PowerPoint, OTP, BMP, Presentation, PHP"
description: OTP से BMP PHP रूपांतरण के लिए नमूना कोड। OTP फ़ाइलों को BMP फ़ाइलों में बैच रूपांतरण के लिए PowerPoint PHP API का उपयोग करें।
slides_design_update_10_2026: true
---

{{< blocks/products/pf/slides-design-update-10-2026/page >}}

{{< blocks/products/pf/slides-design-update-10-2026/hero h1="PHP में OTP को BMP में बदलें" h2="OTP को BMP में बदलने के लिए शक्तिशाली पावरपॉइंट PHP लाइब्रेरी"
  codeSamplesLink="https://github.com/aspose-slides"
  liveDemosLink="https://products.aspose.app/slides/family"
  downloadLink="https://downloads.aspose.com/slides/php-java"
  learnLink="https://docs.aspose.com/slides/php-java/"
  pricingLink="https://purchase.aspose.com/pricing/slides/php-java/" >}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP में OTP को BMP में बदलें" %}}

प्रोग्राम के रूप में OTP फ़ाइलों को BMP में कनवर्ट करने की आवश्यकता है? [*Aspose.Slides for PHP by Java*](https://products.aspose.com/slides/hi/php-java/) का उपयोग करके कोई भी डेवलपर PHP कोड की कुछ पंक्तियों के साथ OTP को BMP फ़ॉर्मैट में बदल सकता है .

एक आधुनिक प्रेजेंटेशन प्रोसेसिंग एपीआई के रूप में, Aspose.Slides for PHP OTP से BMP जल्दी से बनाता है। सीधे अपने [ब्राउज़र](https://products.aspose.app/slides/conversion) में OTP से BMP रूपांतरण की गुणवत्ता का परीक्षण करें। Aspose PowerPoint PPTX लाइब्रेरी आपको OTP फाइलों को कई लोकप्रिय प्रारूपों में बदलने की अनुमति देती है।

आप निम्न आदेश का उपयोग करके [संगीतकार](https://packagist.org/packages/aspose/slides) से पुस्तकालय स्थापित कर सकते हैं:

{{< blocks/products/pf/slides-design-update-10-2026/install >}}
{{< blocks/products/pf/slides-design-update-10-2026/code title="कंसोल/टर्मिनल" >}}
```console
> composer require aspose/slides 

```
{{< /blocks/products/pf/slides-design-update-10-2026/code >}}
{{< /blocks/products/pf/slides-design-update-10-2026/install >}}

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section h2="PHP में OTP को BMP के रूप में सेव करें" %}}

OTP से BMP रूपांतरण प्रक्रिया का प्रदर्शन देखने के लिए निःशुल्क ऐप का उपयोग करें।

{{% /blocks/products/pf/slides-design-update-10-2026/section %}}

{{% blocks/products/pf/slides-design-update-10-2026/section variant="code" %}}

{{< blocks/products/pf/slides-design-update-10-2026/code title="यह नमूना कोड OTP से BMP PHP रूपांतरण दिखाता है" >}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.otp");
try
{
    for ($i = 0; $i < java_values($pres->getSlides()->size()); $i++)
    {
        $bmp = $pres->getSlides()->get_Item($i)->getThumbnail(2, 2);
        $imageio = new Java("javax.imageio.ImageIO");
        $javafile = new Java("java.io.File", "slide_". $i .".bmp");
        $imageio->write($bmp, "BMP", $javafile);
    }
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
{{< blocks/products/pf/slides-design-update-10-2026/steps title="PHP में OTP को BMP में कैसे बदलें" intro="PHP का उपयोग करके OTP फ़ाइल को BMP में बदलने के लिए ये चरण हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}प्रस्तुति वर्ग के उदाहरण के साथ OTP फ़ाइल लोड करें{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}आउटपुट फ़ाइल पथ और SaveFormat को निर्दिष्ट करते समय `सेव` विधि को कॉल करें। BMP पैरामीटर के रूप में{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}OTP फ़ाइल निर्दिष्ट पथ पर सहेजी जाएगी{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}

{{< blocks/products/pf/slides-design-update-10-2026/steps title="सिस्टम आवश्यकताएं" intro="PHP रूपांतरण नमूना स्रोत कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।" >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}PHP 7 स्थापित करें, PHP को सिस्टम `PATH` चर में पथ जोड़ें और `php.ini` फ़ाइल में `allow_url_include` को `चालू` पर सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}JRE 8 स्थापित करें। `JAVA_HOME` पर्यावरण चर को स्थापित JRE स्थान के पथ के रूप में सेट करें।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< blocks/products/pf/slides-design-update-10-2026/step >}}अपाचे टॉमकैट 8.0 स्थापित करें (देखें [अधिक](https://docs.aspose.com/slides/php-java/installation/))।{{< /blocks/products/pf/slides-design-update-10-2026/step >}}
{{< /blocks/products/pf/slides-design-update-10-2026/steps >}}
{{< /blocks/products/pf/slides-design-update-10-2026/pair >}}

{{< blocks/products/pf/slides-design-update-10-2026/converter appName="conversion" extension=""
  title="Free App to Convert OTP to BMP"
  description="[Try our free Video app](https://products.aspose.app/slides/video/)" >}}

{{< blocks/products/pf/slides-design-update-10-2026/other-conversions title="अन्य समर्थित रूपांतरण" subTitle="आप OTP को कई अन्य फ़ाइल स्वरूपों में भी बदल सकते हैं। अन्य समर्थित रूपांतरण नीचे देखें" >}}
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-fodp/" name="OTP TO FODP" description="ओपन डॉक्यूमेंट फ्लैट एक्सएमएल प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-gif/" name="OTP TO GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-html/" name="OTP TO HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-jpg/" name="OTP TO JPG" description="जेपीईजी छवि" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-odp/" name="OTP TO ODP" description="OpenDocument प्रस्तुति स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-pdf/" name="OTP TO PDF" description="संवहन दस्तावेज़ स्वरूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-png/" name="OTP TO PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-pot/" name="OTP TO POT" description="Microsoft PowerPoint टेम्पलेट फ़ाइलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-potm/" name="OTP TO POTM" description="Microsoft PowerPoint टेम्पलेट फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-potx/" name="OTP TO POTX" description="माइक्रोसॉफ्ट पावरपॉइंट टेम्पलेट प्रेजेंटेशन" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-pps/" name="OTP TO PPS" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-ppsm/" name="OTP TO PPSM" description="मैक्रो-सक्षम स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-ppsx/" name="OTP TO PPSX" description="पावरपॉइंट स्लाइड शो" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-ppt/" name="OTP TO PPT" description="माइक्रोसॉफ्ट पावरपॉइंट 97-2003" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-pptm/" name="OTP TO PPTM" description="मैक्रो-सक्षम प्रस्तुति फ़ाइल" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-pptx/" name="OTP TO PPTX" description="एक्सएमएल प्रस्तुति प्रारूप खोलें" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-svg/" name="OTP TO SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-swf/" name="OTP TO SWF" description="एसडब्ल्यूएफ प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-tiff/" name="OTP TO TIFF" description="टैग की गई छवि प्रारूप" >}}  
{{< blocks/products/pf/slides-design-update-10-2026/other-conversion href="https://products.aspose.com/slides/hi/php-java/conversion/otp-to-xps/" name="OTP TO XPS" description="एक्सएमएल पेपर निर्दिष्टीकरण" >}}
{{< /blocks/products/pf/slides-design-update-10-2026/other-conversions >}}

{{< /blocks/products/pf/slides-design-update-10-2026/page >}}
