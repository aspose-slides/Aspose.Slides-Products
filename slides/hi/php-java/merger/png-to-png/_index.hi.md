---
title: PHP में PNG छवियों को मर्ज करें
url: /hi/php-java/merger/png-to-png/
keywords: PNG, PNG को PNG में मर्ज करें, PNG से जुड़ें, PNG, PHP API, PHP लाइब्रेरी को मिलाएं
description: PHP में PNG को PNG में मर्ज करें। पीएनजी फाइलों को गठबंधन करने के लिए PHP लाइब्रेरी एपीआई का प्रयोग करें
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/feature-page-wrap >}}

{{< blocks/products/pf/feature-page-header h1="PNG को PHP में मर्ज करें" h2="PHP कोड का उपयोग करके PNG छवियों को मर्ज करने के लिए हाई-स्पीड और क्रॉस-प्लेटफ़ॉर्म PHP लाइब्रेरी" >}}

{{% blocks/products/pf/feature-page-section h2="Aspose.Slides का उपयोग करके PNG को PNG में मर्ज करें" %}}

[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) एक शक्तिशाली PHP लाइब्रेरी है जिसका इस्तेमाल प्रेजेंटेशन, इमेज और अन्य फाइलों को मर्ज और मैनीपुलेट करने के लिए किया जाता है। जब आप पीएनजी को पीएनजी में विलय करते हैं, तो आप एक तस्वीर प्राप्त करने के लिए प्रभावी रूप से दो छवियों को जोड़ रहे हैं।

{{% /blocks/products/pf/feature-page-section %}}




{{% blocks/products/pf/feature-page-section  h2="PHP में PNG को PNG में मर्ज करें" %}}
[**Aspose.Slides for PHP via Java**](https://products.aspose.com/slides/hi/php-java/) का उपयोग करके, आप कोड की कुछ पंक्तियों के साथ PNG फ़ाइलों को जल्दी से मर्ज कर सकते हैं

{{% blocks/products/pf/agp/code-block title="PNG को PNG में मर्ज करने के लिए PHP कोड" offSpacer="true" %}}
```php

<?php
require_once("http://localhost:8080/JavaBridge/java/Java.inc");
require_once("lib/aspose.slides.php");

$pres = new Presentation();
try
{
    $slide = $pres->getSlides()->get_Item(0);
    
    $filename1 = 'image1.png';
    $f1 = fopen($filename1, 'r');
    if ($f1) {
        $contents1 = fread($f1, filesize($filename1));
        fclose($f1);
    }

    $filename2 = 'image1.png';
    $f2 = fopen($filename2, 'r');
    if ($f2) {
        $contents2 = fread($f2, filesize($filename2));
        fclose($f2);
    }
    
    $image1 = $pres->getImages()->addImage($contents1);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 0, 0, 360, 540, $image1);
    
    $image2 = $pres->getImages()->addImage($contents2);
    $slide->getShapes()->addPictureFrame(ShapeType::Rectangle, 360, 0, 360, 540, $image2);

    $img = $pres->getSlides()->get_Item(0)->getThumbnail(2, 2);
    $imageio = new Java("javax.imageio.ImageIO");
    $javafile = new Java("java.io.File", "merged-image.png");
    $imageio->write($img, "PNG", $javafile);
}
finally
{
    if ($pres != null) $pres->dispose();
}
?>
```
{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/feature-page-section %}}




{{< blocks/products/pf/feature-page-section  h2="PHP में PNG को कैसे मर्ज करें" >}}


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
उन PNG फ़ाइलों को लोड करें जिन्हें आप चित्र फ़्रेम के रूप में मर्ज करना चाहते हैं।
{{< /blocks/products/pf/agp/step-autogen >}}

{{< blocks/products/pf/agp/step-autogen >}}
परिणामी PNG छवि सहेजें।
{{< /blocks/products/pf/agp/step-autogen >}}


{{< /blocks/products/pf/agp/steps-block-autogen >}}


{{< /blocks/products/pf/feature-page-section >}}




{{< blocks/products/pf/agp/other-supported-section title="अन्य फ़ाइलें मर्ज करें" subTitle="आप एकल फ़ाइल प्राप्त करने के लिए फ़ाइलों को अन्य स्वरूपों में भी संयोजित कर सकते हैं" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/jpg-to-jpg/" name="JPG TO JPG" >}}    
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/html-to-html/" name="HTML TO HTML" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/image-to-image/" name="IMAGE TO IMAGE" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/jpg-to-pdf/" name="JPG TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/image-to-pdf/" name="IMAGE TO PDF" >}}  
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/png-to-pdf/" name="PNG TO PDF" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/svg-to-png/" name="SVG TO PNG" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/image-to-bmp/" name="IMAGE TO BMP" >}} 
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/slides/hi/php-java/merger/html-to-image/" name="HTML TO IMAGE" >}}  
  


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}