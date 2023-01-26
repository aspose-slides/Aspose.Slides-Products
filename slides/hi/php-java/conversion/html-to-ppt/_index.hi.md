---
title: PHP में HTML को PPT में बदलें
url: /hi/php-java/conversion/html-to-ppt/
keywords: HTML से PPT, HTML को PPT में कन्वर्ट करें, PHP API, PHP लाइब्रेरी, HTML, PPT
description: PHP में HTML को PPT में बदलें। HTML फ़ाइलों को PPT में कनवर्ट करने के लिए PowerPoint PHP API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP में HTML को PPT में बदलें" h2="शक्तिशाली PowerPoint PHP लाइब्रेरी जो Microsoft या Open Office, Adobe PDF जैसे किसी सॉफ़्टवेयर के उपयोग के बिना Microsoft PowerPoint और OpenOffice प्रस्तुति फ़ाइलों को बनाने, मर्ज करने, निरीक्षण करने या परिवर्तित करने की क्षमता वाले अनुप्रयोगों को विकसित करने में मदद करती है।" >}}

{{% blocks/products/pf/feature-page-section h2="PHP में HTML को PPT में बदलें" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) प्रस्तुति फ़ाइलों को बनाने और उनमें हेरफेर करने के लिए एक शक्तिशाली PHP लाइब्रेरी है। इसके अलावा, यह HTML को PPT में बदलने के लचीले तरीके प्रदान करता है। **Aspose.Slides for PHP via Java** का उपयोग करके, कोई भी डेवलपर या एप्लिकेशन HTML को PPT फ़ाइलों में PHP कोड की कुछ पंक्तियों के साथ परिवर्तित कर सकता है।

एक आधुनिक दस्तावेज़ प्रसंस्करण एपीआई के रूप में, PHP के लिए Aspose.Slides HTML फ़ाइलों को PPT फ़ाइल स्वरूपों में तेज़ी से निर्यात करता है। Aspose PowerPoint लाइब्रेरी आपको HTML को PPT और कई अन्य फ़ाइल स्वरूपों में बदलने की अनुमति देती है

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP का उपयोग करके HTML को PPT में बदलें" %}}
HTML को PPT में बदलने के लिए, आपको HTML फ़ाइल से प्रस्तुतिकरण बनाना होगा और इसे PPT के रूप में सहेजना होगा।

{{% blocks/products/pf/agp/code-block title="HTML को PPT में बदलने के लिए PHP कोड" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
        
$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $filename = 'file.html';
    $f = fopen($filename, 'r');
    if ($f) {
        $contents = fread($f, filesize($filename));
        fclose($f);
    }
    
    $pres->getSlides()->addFromHtml($contents);        
    $pres->save("output.ppt", SaveFormat::Ppt);        
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```


{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PHP API के लिए Aspose.Slides का उपयोग करके HTML को PPT में कैसे बदलें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="ये PHP में HTML को PPT में बदलने के चरण हैं।" >}}

{{< blocks/products/pf/agp/step-autogen >}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) इंस्टॉल करें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
अपने PHP प्रोजेक्ट में लाइब्रेरी संदर्भ (लाइब्रेरी आयात करें) जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
PHP में स्रोत HTML फ़ाइलें खोलें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणाम को PPT फ़ाइल के रूप में सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}

{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="HTML को अन्य समर्थित प्रारूपों में बदलें" subTitle="आप HTML को भी रूपांतरित कर सकते हैं और अन्य फ़ाइल स्वरूपों में सहेज सकते हैं। नीचे सभी समर्थित प्रारूप देखें" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-image/" name="HTML TO IMAGE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-jpg/" name="HTML TO JPG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-pdf/" name="HTML TO PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-pptx/" name="HTML TO PPTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-png/" name="HTML TO PNG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-tiff/" name="HTML TO TIFF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/conversion/html-to-xml/" name="HTML TO XML" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}