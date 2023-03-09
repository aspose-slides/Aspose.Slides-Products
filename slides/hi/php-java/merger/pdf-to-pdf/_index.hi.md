---
title: पीडीएफ फाइलों को PHP में मर्ज करें
url: /hi/php-java/merger/pdf-to-pdf/
keywords: पीडीएफ, पीडीएफ को पीडीएफ में मर्ज करें, पीडीएफ से जुड़ें, पीडीएफ को मिलाएं, पीएचपी एपीआई, पीएचपी लाइब्रेरी
description: PHP में PDF को PDF में मर्ज करें। पीडीएफ फाइलों को गठबंधन करने के लिए PHP लाइब्रेरी एपीआई का प्रयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="पीडीएफ को PHP में मर्ज करें" h2="PHP कोड का उपयोग करके PDF फ़ाइलों को मर्ज करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म PHP लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PDF को PDF में मर्ज करें" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) एक शक्तिशाली PHP लाइब्रेरी है जिसका उपयोग प्रेजेंटेशन, PDF, बनाने, बदलने, मर्ज करने और हेरफेर करने के लिए किया जाता है। और अन्य दस्तावेज। जब आप पीडीएफ को पीडीएफ में मर्ज करते हैं, तो आप प्रभावी रूप से एक पीडीएफ फाइल प्राप्त करने के लिए 2 दस्तावेजों के पृष्ठों को जोड़ रहे हैं। Aspose.Slides आपको विभिन्न तरीकों से PDF को मर्ज करने की अनुमति देता है। आप PDF को उनके सभी आकार, स्टाइल, टेक्स्ट, फ़ॉर्मेटिंग आदि के साथ मर्ज कर सकते हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PHP में PDF को PDF में मर्ज करें" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ पीडीएफ फाइलों को जल्दी से मर्ज कर सकते हैं

{{% blocks/products/pf/agp/code-block title="पीडीएफ को पीडीएफ में मर्ज करने के लिए पीएचपी कोड" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $pres->getSlides()->removeAt(0);
    
    $pres->getSlides()->addFromPdf("document1.pdf");
    $pres->getSlides()->addFromPdf("document2.pdf");

    $pres->save("merged-pdf.pdf", SaveFormat::Pdf);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="पीडीएफ को PHP में कैसे मर्ज करें" >}}


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
उन पीडीएफ फाइलों को लोड करें जिन्हें आप मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी पीडीएफ को सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/jpg-to-jpg/" name="JPG to JPG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/png-to-png/" name="PNG TO PNG" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}