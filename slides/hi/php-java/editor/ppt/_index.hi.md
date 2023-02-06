---
title: PHP में PPT संपादित करें
url: /hi/php-java/editor/ppt/
keywords: संपादित करें PPT, संपादित करें PowerPoint, PPT, PowerPoint, PHP API, PHP लाइब्रेरी
description: PHP में PPT संपादित करें। PPT फ़ाइलों को संपादित करने के लिए PHP लाइब्रेरी API का उपयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PHP में PPT संपादित करें" h2="PHP कोड का उपयोग करके PPT संपादित करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म PHP लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PPT संपादित करें" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) प्रस्तुतियों को जल्दी और आसानी से संपादित करने के लिए एक शक्तिशाली PHP लाइब्रेरी है। यह उपयोगकर्ताओं को कुछ ही समय में पेशेवर दिखने वाली स्लाइड बनाने में मदद करने के लिए कई प्रकार की सुविधाएँ प्रदान करता है। Aspose के साथ, उपयोगकर्ता अपनी प्रस्तुति में पाठ संपादित कर सकते हैं, चित्र, एनिमेशन और बदलाव जोड़ सकते हैं और साथ ही विभिन्न स्वरूपण विकल्प जैसे कि फ़ॉन्ट प्रकार और रंग चयन भी लागू कर सकते हैं। इसके अतिरिक्त, पुस्तकालय PowerPoint (PPT) फ़ाइलों और OpenOffice प्रस्तुति (ODP) दोनों स्वरूपों के लिए समर्थन प्रदान करता है जो किसी भी अनुकूलता के मुद्दों के बिना विभिन्न प्लेटफार्मों में प्रस्तुतियों को साझा करना पहले से कहीं अधिक आसान बना देता है। अपनी अगली प्रस्तुति बनाते या संपादित करते समय Aspose की लाइब्रेरी की शक्ति का लाभ उठाकर आप सुनिश्चित होंगे कि आपकी स्लाइड हर बार शानदार दिखेंगी!
आप किसी PPT फ़ाइल में टेक्स्ट की एक नई पंक्ति जोड़कर उसे संपादित कर सकते हैं। 

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="PHP में PPT संपादित करें" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) का इस्तेमाल करके, आप PPT दस्तावेज़ में टेक्स्ट की एक नई लाइन जोड़ सकते हैं. कोड की कुछ पंक्तियाँ।

{{% blocks/products/pf/agp/code-block title="संपादन के लिए PHP कोड PPT" offSpacer="true" %}}

```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");
 
use aspose\slides\Presentation;
use aspose\slides\SaveFormat;
 
$pres = new Presentation("input.ppt");
try
{
    $slide = $pres->getSlides()->get_Item(0);     
    $shape = $slide->getShapes()->addAutoShape(ShapeType::Rectangle, 10, 10, 100, 50);
    $shape->getTextFrame()->setText("New text");

    $pres->save("input.ppt", SaveFormat::Ppt);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-section  h2="PHP में PPT को कैसे संपादित करें" >}}

{{< blocks/products/pf/agp/steps-block-autogen name="" >}}


{{< blocks/products/pf/agp/step-autogen >}}
**Aspose.Slides for PHP via Java** इंस्टॉल करें। देखें [**इंस्टॉलेशन**](https://docs.aspose.com/slides/php-java/installation/)।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पुस्तकालय को अपनी परियोजना में संदर्भ के रूप में जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
प्रेजेंटेशन क्लास का एक उदाहरण बनाएं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
वह PPT प्रस्तुति लोड करें जिसे आप संपादित करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
पाठ की एक नई पंक्ति जोड़ें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिवर्तित फ़ाइल सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य फाइलों को संपादित करें" subTitle="आप फ़ाइलों को अन्य स्वरूपों में भी संपादित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/fodp/" name="FODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/html/" name="HTML" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/odp/" name="ODP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/otp/" name="OTP" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/pdf/" name="PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/pot/" name="POT" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/potm/" name="POTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/potx/" name="POTX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/pps/" name="PPS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/ppsm/" name="PPSM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/ppsx/" name="PPSX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/pptm/" name="PPTM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/editor/pptx/" name="PPTX" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}